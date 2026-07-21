---
myst:
  html_meta:
    description: Join Ubuntu Server to Microsoft Active Directory domains and forests using Winbind with rid or autorid backends.
---

```{tags} Index, Windows
```

(how-to-active-directory-integration)=
# Active Directory integration

If you have a Microsoft Active Directory domain set up, you can join your Ubuntu Server to it. There are a number of choices you need to make about your setup before you can begin, so you may want to refer to the Configuration section first.


## Introduction

```{toctree}
:titlesonly:

intro-to-AD-integration
```

## Configuration

This section will talk you through the options available and help you make the appropriate choices for your setup.

```{toctree}
:titlesonly:

Choosing an integration method <choosing-an-integration-method>
Security identifiers (SIDs) <security-identifiers-sids>
Identity Mapping (idmap) backends <identity-mapping-idmap-backends>
The rid idmap backend <the-rid-idmap-backend>
The autorid idmap backend <the-autorid-idmap-backend>
```

## Integration

If you have a Microsoft Active Directory domain set up, you can join your Ubuntu Server to it. There are a number of choices you need to make about your setup before you can begin, so you may want to refer to our {ref}`AD integration explanations <explanation-active-directory-integration>` first.

```{toctree}
:titlesonly:

Prepare to join a domain <join-a-domain-with-winbind-preparation>
Join a simple domain with the rid backend <join-a-simple-domain-with-the-rid-backend>
Join a forest with the rid backend <join-a-forest-with-the-rid-backend>
Join a forest with the autorid backend <join-a-forest-with-the-autorid-backend>
```



