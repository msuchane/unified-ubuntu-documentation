(network-tools)=
# Network tools


The Domain Name Service (DNS) maps IP addresses to fully qualified domain names (FQDN). The {ref}`DNS Security Extensions (DNSSEC) <dnssec>` allow DNS data to be verified.

```{toctree}
:titlesonly:

Set up a name server (DNS) <install-dns>
```

Open vSwitch (OVS) with the Data Plane Development Kit (DPDK) provides virtual switching for network automation in virtualized environments. In our how-to section, we show how to set up virtual switching using Open vSwitch (OVS) and the Data Plane Development Kit (DPDK) library. This page discusses DPDK in more detail.


```{toctree}
:titlesonly:

Use Open vSwitch with DPDK <dpdk-with-open-vswitch>
The DPDK library <about-dpdk>
```

NVIDIA DOCA provides the software components required for high-performance networking with NVIDIA BlueField and ConnectX devices.

```{toctree}
:titlesonly:

Install DOCA-OFED <install-doca-ofed>
```

## Traffic management

Traffic shaping allows you to prioritize certain types of network traffic, reducing latency for interactive applications when using Ubuntu as a router.

```{toctree}
:titlesonly:

Traffic shaping with tc and CAKE <traffic-shaping-tc-cake>
```
