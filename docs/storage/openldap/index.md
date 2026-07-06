---
myst:
  html_meta:
    description: Install and configure OpenLDAP on Ubuntu Server with guides for access control, replication, TLS, user management, and backup.
---

(how-to-openldap)=
# OpenLDAP

The Lightweight Directory Access Protocol, or LDAP, is a protocol for managing hierarchical data and accessing directories. The open source implementation used in Ubuntu is OpenLDAP.

These guides are intended to be sequential, so following them in the order presented below is suggested.

```{toctree}
:titlesonly:

intro-to-openldap
install-openldap
Set up access control <access-control>
OpenLDAP with replication <replication>
User and group management <users-and-groups>
OpenLDAP and TLS <ldap-and-tls>
Backup and restore <backup-and-restore>
Introduction to passthrough authentication <ldap-saslauthd-authentication-intro>
Passthrough authentication with Kerberos <ldap-saslauthd-kerberos>
Set up an LDAP client <ldap-client>
```

