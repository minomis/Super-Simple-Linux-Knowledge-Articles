# Super Simple Linux Knowledge Articles #
*"that are really easy to understand"*

---

## Table of Contents ##
[How to extract files from a .rpm](#how-to-extract-files-from-a-.rpm)
[How to extract files from a .deb](#how-to-extract-files-from-a-.deb)
---

### How to extract files from a .rpm ###

```console
rpm2cpio ./packagecloud-test-1.1-1.x86_64.rpm | cpio -idmv
```

### How to extract files from a .deb ###

```console
dpkg-deb -R
```
