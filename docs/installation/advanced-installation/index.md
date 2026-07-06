---
myst:
  html_meta:
    description: Ubuntu Server installation guides for automatic installs, netboot, and architecture-specific setups including amd64, arm64, ppc64el, and s390x.
---

(advanced-installation)=
# Advanced installation

If you are new to Ubuntu, we recommend our {ref}`basic installation <basic-installation>` tutorial to get you started.

This list of guides contains installation instructions for architecture-specific and more advanced setups. Select your preferred architecture to see which guides are available.

::::{tab-set}

:::{tab-item} **amd64**

* {ref}`Netboot install <how-to-netboot-the-server-installer-on-amd64>`

:::

:::{tab-item} **arm64**

* {ref}`Netboot install <netboot-the-server-installer-via-uefi-pxe-on-arm-aarch64-arm64-and-x86-64-amd64>`
* {ref}`Choose between the arm64 and arm64+largemem installer options <choosing-between-the-arm64-and-arm64-largemem-installer-options>`
:::

:::{tab-item} **ppc64el**

* {ref}`Netboot install <netboot-the-live-server-installer-on-ibm-power-ppc64el-with-petitboot>`
* {ref}`Virtual CD-ROM and Petitboot install <how-to-start-a-live-server-installation-on-ibm-power-ppc64el-with-a-virtual-cd-rom-and-petitboot>`
:::

:::{tab-item} **s390x**

* {ref}`Install via z/VM <interactive-live-server-installation-on-ibm-z-vm-s390x>`
* {ref}`Non-interactive IBM z/VM autoinstall <non-interactive-ibm-z-vm-autoinstall-s390x>`
* {ref}`Install via LPAR <interactive-live-server-installation-on-ibm-z-lpar-s390x>`
* {ref}`Non-interactive IBM Z LPAR autoinstall <non-interactive-ibm-z-lpar-autoinstall-s390x>`
:::

::::


```{toctree}
:hidden:

amd64 netboot install <how-to-netboot-the-server-installer-on-amd64>
arm64 netboot install <netboot-the-server-installer-via-uefi-pxe-on-arm-aarch64-arm64-and-x86-64-amd64>
Choose between the arm64 and arm64+largemem installer options <choosing-between-the-arm64-and-arm64-largemem-installer-options>
ppc64el netboot install <netboot-the-live-server-installer-on-ibm-power-ppc64el-with-petitboot>
Virtual CD-ROM and Petitboot install on ppc64el <how-to-start-a-live-server-installation-on-ibm-power-ppc64el-with-a-virtual-cd-rom-and-petitboot>
s390x install via z/VM <interactive-live-server-installation-on-ibm-z-vm-s390x>
Non-interactive IBM z/VM autoinstall (s390x) <non-interactive-ibm-z-vm-autoinstall-s390x>
s390x install via LPAR <interactive-live-server-installation-on-ibm-z-lpar-s390x>
Non-interactive IBM Z LPAR autoinstall (s390x) <non-interactive-ibm-z-lpar-autoinstall-s390x>
```
