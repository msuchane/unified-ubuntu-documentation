(time)=
# Time

## Time synchronization

The Network Time Protocol (NTP) synchronizes time over a network. Ubuntu uses `chrony` by default to handle this. However, users can install and use `timedatectl`/`timesyncd` instead if preferred.

```{toctree}
:titlesonly:

Time sync with chrony <chrony-client>
Time sync with timedatectl and timesyncd <timedatectl-and-timesyncd>
Serving time with chrony <serve-ntp-with-chrony>
```

* {ref}`About time synchronisation <about-time-synchronisation>` discusses the Network Time Protocol (NTP) and how it works

```{toctree}
:hidden:

Time synchronisation <about-time-synchronisation>
```
