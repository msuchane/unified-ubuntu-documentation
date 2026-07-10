---
myst:
  html_meta:
    description: Understanding High Availability concepts including redundancy, failover, load balancing, and DRBD for minimal downtime in Ubuntu Server.
---

(high-availability)=
# High Availability on Ubuntu

High Availability is a way to ensure minimal downtime if and when system failures occur by using redundancy, failover and load balancing to keep services running.

## Introduction

* {ref}`Introduction to High Availability <introduction-to-high-availability>`

## Key concepts

* {ref}`Pacemaker resource agents <pacemaker-resource-agents>`
* {ref}`Pacemaker fence agents <pacemaker-fence-agents>`

```{toctree}
:hidden:

Introduction to HA <intro-to-high-availability>
Pacemaker resource agents <pacemaker-resource-agents>
Pacemaker fence agents <pacemaker-fence-agents>
```

## `crmsh` migration

In Ubuntu 23.04 (Lunar) and onward, `pcs` became the recommended and supported tool for managing Pacemaker clusters. The 23.04 release is the last release where `crmsh` is available.

To migrate from `crmsh` to `pcs`, refer to our reference table of {ref}`corresponding commands <migrate-from-crmsh-to-pcs>`.

```{toctree}
:titlesonly:

Migrate from crmsh to pcs <migrate-from-crmsh-to-pcs>
```

## DRBD

Distributed Replicated Block Device (DRBD) mirrors block devices between multiple hosts. This guide shows how to install and configure a DRBD.

* {ref}`Install a Distributed Replicated Block Device <install-drbd>`

```{toctree}
:titlesonly:

Distributed Replicated Block Device (DRBD) <install-drbd>
```
