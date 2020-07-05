# Super Simple Linux Knowledge Articles #
*"that are really easy to understand"*

---

## Table of Contents ##

**Packaging**
    1. [Extract files from a DEB file](#extract-files-from-a-deb-file)
    1. [Extract files from a RPM file](#extract-files-from-a-rpm-file)

---

### Extract files from a DEB file ###

```console
dpkg-deb -R <insert the DEB file you want to extract here> <insert where you want the extracted DEB file to go>
```

### Extract files from a RPM file ###

```console
rpm2cpio <insert the RPM file you want to extract here> | cpio -idmv -D <insert where you want the extracted RPM file to go>
```

---
