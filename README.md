# FreeBSD Cheatsheet
> The handbook is great, but this is the short one.

## Table of Contents

- [Kernel](#kernel)


## Kernel

### Install Kernel Sources
```bash
svn checkout http://svn.freebsd.org/base/release/10.2.0/ /usr/src
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
