## EIP - Extensible In-band Processing

EIP extends the functionality of IPv6 layer to support the requirements of future Internet services / 6G networks.

In a nutshell, IPv6 nodes can read/write EIP information in packet headers to implement different use cases (e.g. contractual networking, deterministic networking, network slicing).

Find [here](https://tinyurl.com/eip4coinrg) a presentation about EIP.

EIP provides a common solution which can be tailored for the different use cases. Each use case will have its own specific architectural aspects and protocol specifications.

### Special Interest Group on EIP

The mailling list of the Interest Group for EIP is [eip@postino.cnit.it](mailto:eip@postino.cnit.it). Subscribe to the mailing list and access the list archives [here](http://postino.cnit.it/cgi-bin/mailman/listinfo/eip).

The wiki of the EIP group is [here](https://github.com/eip-home/eip/wiki/Wiki-for-EIP)

### EIP documentation 

Work in progress: EIP problem statement, use cases, architecture, protocol specifications.

The status of the work is available [here](https://github.com/eip-home/eip/wiki/EIP-documentation)

### EIP prototypes and testbeds

An open source prototype of EIP for Linux (based on eBPF) is under development and will be soon available. The EIP prototype builds upon the [HIKe/eCLAT framework](https://hike-eclat.readthedocs.io/).

The basic EIP prototype is a docker container which includes:
- the development environment for EIP based on HIKe/eCLAT
- a minimal testbed with a Traffic Generator (TG) node and a "System Under Test" (SUT) node that implements EIP functionality.

<!--- img source :
      https://docs.google.com/drawings/d/10RUFpz28TDxJ-PgvMalNpm3tdtjR0NooK93X4GYNeI8 
      export the slide as .png, and upload in docs/images with the same name --->
<center><img src="./images/basic-EIP-testbed.png" width="610"></center>

<!---
![basic-EIP-testbed.png](<./images/basic-EIP-testbed.png>)
---> 

A more advanced testbed is a Virtual Machine (available as an .ova image for Virtualbox and VMware hypervisors). In the Virtual Machine it is possible to deploy an emulated network with 8 routers and 15 hosts. The 8 routers emulate an IPv6 backbone with dynamic routing (ISIS protocol). Routers and hosts in the emulated network can execute the EIP prototype as needed to demonstrate complex scenarios involving several nodes.

### Github page

https://github.com/eip-home/eip/

