---
myst:
  html_meta:
    description: Ubuntu Server networking guides covering Netplan configuration, DNS/DNSSEC, FTP, DHCP, time synchronization, and network troubleshooting.
---

(dhcp)=
# DHCP

The Dynamic Host Configuration Protocol (DHCP) handles automatic IP address assignment.

* {ref}`About DHCP <about-dhcp>` gives details about DHCP and how it works

```{toctree}
:hidden:

About DHCP <about-dhcp>
```

## Set up DHCP

Set up Dynamic Host Configuration Protocol (DHCP) for automatic IP address assignment for devices on your network. There are two DHCP servers available in Ubuntu: `isc-kea` is the most modern, and is available from 23.04 onward.

```{toctree}
:titlesonly:

Install DHCP isc-kea <install-isc-kea>
Install DHCP isc-dhcp-server <install-isc-dhcp-server>
```

