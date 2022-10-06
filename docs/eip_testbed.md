# EIP prototypes and experiments

The open source prototype of EIP for Linux (based on eBPF) is based on two main components:

1. Scapy based packet generator / dissector
1. EIP aware router

The Scapy based packet generator is a fork of the scapy project, available at: https://github.com/eip-home/scapy/tree/eip

The EIP aware router is based on eBPF/XDP. It builds upon the [HIKe/eCLAT framework](https://hike-eclat.readthedocs.io/).

The basic EIP prototype is a docker container which includes:
- the development environment for EIP 
- a testbed with 4 “namespaces” that implement EIP Packet generator/dissector and EIP aware router

The topology that is provided for the experiments and tests is shown hereafter.

<!--- img source :
      https://docs.google.com/drawings/d/10RUFpz28TDxJ-PgvMalNpm3tdtjR0NooK93X4GYNeI8 
      export the slide as .png, and upload in docs/images with the same name --->
<!---
![basic-EIP-testbed.png](<./images/basic-EIP-testbed.png>)

<center><img src="https://docs.google.com/drawings/d/e/2PACX-1vRfqnSlb0n8yimc4XHUEBHkQoZykFunajJeiAZoSuArt0wDYQUeA6HelRWCCsDA9fgU-fXmJouu7kr6/pub?w=776&h=330" width="610"></center> 

---> 

PROVIDE THE INSTRUCTIONS TO CLONE THE GIT REPOSITORY

PROVIDE THE INSTRUCTIONS TO GENERATE AND DISSECT THE PACKETS

- PATH TRACING
- GEO TAGGING

THE INSTRUCTION TO RUN THE EXPERIMENTS FOR PATH TRACING ON HIKE ECLAT ARE PROVIDED HERE 
https://hike-eclat.readthedocs.io/en/latest/experiments.html#path-tracing-example



