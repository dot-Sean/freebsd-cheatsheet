# FreeBSD Cheatsheet
> The handbook is great, but this is the short one.

## Table of Contents

- [Kernel](#kernel)


## Kernel

### Install Kernel Sources
```bash
fetch ftp://ftp.freebsd.org/pub/FreeBSD/releases/amd64/10.3-RELEASE/src.txz
tar -C / -xvzf src.txz
```


## Updates

### Install portmaster
```bash
cd /usr/ports/ports-mgmt/portmaster && \
make install clean
```

### Install FreeBSD ports collection
```bash
portsnap fetch extract
```

### Upgrade FreeBSD ports collection
```bash
portsnap fetch update
```

### Fetch binary updates
```bash
freebsd-update fetch install
```
