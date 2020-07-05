# Super Simple Linux Knowledge Articles #
*"that are really easy to understand"*

---

## Table of Contents ##
1. [How to extract files from a rpm file](#how-to-extract-files-from-a-rpm-file)
1. [How to extract files from a deb file](#how-to-extract-files-from-a-deb-file)

---

### How to extract files from a rpm file ###

```console
rpm2cpio ./packagecloud-test-1.1-1.x86_64.rpm | cpio -idmv
```

### How to extract files from a deb file ###

```console
dpkg-deb -R
```
