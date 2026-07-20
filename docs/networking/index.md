---
myst:
  html_meta:
    description: Ubuntu Server networking guides covering Netplan configuration, DNS/DNSSEC, FTP, DHCP, time synchronization, and network troubleshooting.
---

```{tags} Index
```

(networking)=
# Networking

## Introduction

If you are new to networking, you should start with these pages to obtain an understanding of the key terms and concepts.

```{toctree}
:titlesonly:

intro-to-networking
networking-key-concepts
about-netplan
configuring-networks
time/index
network-tools/index
sharing/index
dhcp/index
```


## Configuration

Network configuration in Ubuntu is handled through Netplan. See our general walk-through on {ref}`configuring-networks`, or refer to [the Netplan documentation](https://netplan.readthedocs.io/en/stable/) for more specific instructions.

Network configuration in Ubuntu is managed using Netplan. Find out more {ref}`About Netplan <about-netplan>` or get started with our {ref}`network configuration <configuring-networks>` walk-through, which gives a practical demonstration.

## Network shares

Sharing files and resources across a network is a common requirement - this is where the Network File System (NFS) comes in.

* {ref}`network-sharing`

If you need to share network resources between Linux and Windows systems, see our sections on Samba and Active Directory.

* {ref}`Samba <how-to-samba>`
* {ref}`Active Directory integration <how-to-active-directory-integration>`






