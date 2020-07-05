# Super Simple Linux Knowledge Articles #
*"that are really easy to understand"*

---

## Table of Contents ##
1. [Extract files from a rpm file](#extract-files-from-a-rpm-file)
1. [Extract files from a deb file](#extract-files-from-a-deb-file)

---

### Extract files from a rpm file ###

```console
rpm2cpio <insert the rpm you want to extract here> | cpio -idmv -D <insert where you want the extracted rpm to go>
```

### Extract files from a deb file ###

```console
dpkg-deb -R
```

---
