```{tags} Index
```

(explanation-web-services)=
# Web services

Web servers are used to serve web pages when requested by client computers.

## Introduction

```{toctree}
:titlesonly:

intro-to-web-servers
```

## Key concepts

```{toctree}
:titlesonly:

About web servers <about-web-servers>
About Squid proxy servers <about-squid-proxy-servers>
```

## Web services

Web servers are used to serve content over a network (or the Internet). If you want more of an introduction to the different types of web servers available in Ubuntu, check out our {ref}`introduction-to-web-services`.

### Proxy servers

This section shows how to set up a Squid proxy caching server.

```{toctree}
:titlesonly:

Install a Squid server <install-a-squid-server>
```

## Web servers

Two of the most popular web servers in Ubuntu are Apache2 and nginx. This section covers the installation, configuration and extension of both.

### Apache2

```{toctree}
:hidden:

Install Apache2 <install-apache2>
Apache2 settings <configure-apache2-settings>
Apache2 modules <use-apache2-modules>
```

* {ref}`Install Apache2 <install-apache2>`
* {ref}`Configure Apache2 <configure-apache2-settings>`
* {ref}`Extend Apache2 with modules <use-apache2-modules>`

### Nginx

```{toctree}
:hidden:

Install nginx <install-nginx>
nginx settings <configure-nginx>
nginx modules <use-nginx-modules>
```

* {ref}`Install nginx <install-nginx>`
* {ref}`Configure nginx <configure-nginx>`
* {ref}`Extend nginx with modules <use-nginx-modules>`

## Web programming

It is common to set up server-side scripting languages to support the creation of dynamic web content. Whichever scripting language you choose, you will need to have installed and configured your web and database servers beforehand.

```{toctree}
:titlesonly:

Install PHP <install-php>
Install Ruby on Rails <install-ruby-on-rails>
```

