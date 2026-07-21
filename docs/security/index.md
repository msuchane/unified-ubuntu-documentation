---
myst:
  html_meta:
    description: Security concepts and best practices for Ubuntu Server including authentication, cryptography, VPNs, and system hardening strategies.
---

```{tags} Index
```

(security)=
# Security on Ubuntu

:::{toctree}
:maxdepth: 2

intro-to-security
security-suggestions
apparmor
firewalls
user-management
console-security
ssh/index
vpns/index
cryptography/index
dnssec/index
certificates/index
:::

There are many steps you can take to strengthen the security posture of your system. In this section you will find explanations of various concepts related to security.

## General configuration

* {ref}`Introduction to security <introduction-to-security>` for a high-level overview of security in Ubuntu
* {ref}`security-suggestions` provides general recommendations for any Ubuntu system, from straightforward setups to more advanced and complex systems
* {ref}`Users and groups management <user-management>` for setting up user accounts, permissions and password policies
* {ref}`Firewalls <firewalls>` are recommended for network security
* {ref}`AppArmor <apparmor>` limits permissions and access for the software running on your system
* {ref}`Console security <console-security>` for an additional physical security barrier
* {ref}`TPM-backed LUKS decryption <tpm-backed-luks-decryption-with-clevis>` to automate decryption of disks



## Authentication

* {ref}`Introduction to Kerberos <introduction-to-kerberos>`, the network authentication system
* {ref}`Introduction to SSSD <introduction-to-network-user-authentication-with-sssd>`, the collection of daemons that handle authentication from various network sources
* {ref}`About DNSSEC <dnssec>`, the security extension for the Domain Name System (DNS).

These tools are particularly useful for more advanced or complex setups.

* {ref}`how-to-kerberos` is a network authentication protocol providing identity verification for distributed systems
* {ref}`how-to-network-user-authentication-with-sssd` handles authentication, user/group information and authorisation from disparate network sources
* {ref}`Smart card authentication <smart-card-authentication>` provides a physical authentication method

## Cryptography

* {ref}`Our cryptography section <explanation-cryptography>` explains in detail about the different cryptographic libraries and configurations you might encounter.
* {ref}`Certificates <certificates>` are issued, stored and signed by a Certificate Authority (CA) to create trusted connections.
* {ref}`How to obtain certificates <obtain-tls-certificates>` is a step-by-step guide covering Let's Encrypt (via Certbot) and local CA implementation.

The Secure Shell (SSH) cryptographic protocol that provides secure channels on an unsecured network. In Ubuntu, OpenSSH is the most commonly used implementation of SSH. It provides a suite of utilities for encrypting data transfers and can also be used for remote login and authentication.

* {ref}`Obtain TLS certificates <obtain-tls-certificates>` covers both Let's Encrypt (for internet-facing servers) and running your own Certificate Authority (CA) for internal networks

## Virtual Private Network (VPN)

VPNs are commonly used to provide encrypted, secure access to a network. 

* {ref}`Introduction to WireGuard VPN <introduction-to-wireguard-vpn>`, a popular and modern VPN implementation
* {ref}`OpenVPN clients <openvpn-client-implementations>` provides a list of client implementations that can be used with a GUI across platforms.

VPNs are commonly used to provide encrypted, secure access to a network. Two of the most popular choices in Ubuntu are OpenVPN and WireGuard VPN.
 
* {ref}`OpenVPN <install-openvpn>` is a well-established option that supports many platforms besides Linux
* {ref}`how-to-wireguard-vpn` is a modern and performant option that removes a lot of the complexity from configuring a VPN


While a fresh Ubuntu installation is usually safe for immediate use, there are some additional steps you can take to introduce a layered approach to your system's security. If you are new to Ubuntu, you may want to refer to our {ref}`Introduction to security <introduction-to-security>` first for a general overview.
