---
myst:
  html_meta:
    description: Configure Samba on Ubuntu Server as an Active Directory Domain Controller, file server, or print server with share access controls.
---

```{tags} Index
```

(how-to-samba)=
# Samba

A Samba server can be deployed as a full Active Directory Domain Controller (Samba AD/DC), providing authentication to domain users -- whether Linux or Windows. 

## Introduction to Samba

```{toctree}
:titlesonly:

intro-to-samba
```

## With Active Directory

```{toctree}
:titlesonly:

Set up a Samba AD Domain Controller <provision-samba-ad-controller>
Join an Active Directory domain <member-server-in-an-ad-domain>
```

## Set up sharing services

Samba can be configured as a file server or print server, to share files and printers with Windows clients.

```{toctree}
:titlesonly:

Set up a file server <file-server>
Set up a print server <print-server>
```

## Access controls

```{toctree}
:titlesonly:

Share access controls <share-access-controls>
Create AppArmor profile <apparmor-profile>
Mount CIFS shares permanently <mount-cifs-shares-permanently>
```

## Legacy options

These options are now deprecated, but still available. 

```{toctree}
:titlesonly:

NT4 domain controller <nt4-domain-controller-legacy>
OpenLDAP backend <openldap-backend-legacy>
```

## See also

* Explanation: {ref}`introduction-to-samba`
