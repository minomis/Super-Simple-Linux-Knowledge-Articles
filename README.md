# Super Simple Linux Knowledge Articles #
*"that are really easy to understand"*

---

## Table of Contents ##

- **Packaging**
1. [Extract the contents from a DEB file](#extract-the-contents-from-a-deb-file)
1. [Extract the files from a RPM file](#extract-the-files-from-a-rpm-file)
1. [Extract the scripts from a RPM file](#extract-the-scripts-from-a-rpm-file)


---

### Extract the contents from a DEB file ###

```console
dpkg-deb -R <insert the DEB file you want to extract here> <insert where you want the extracted DEB file to go>
```
*# this includes the DEBIAN folder structure*

### Extract the files from a RPM file ###

```console
rpm2cpio <insert the RPM file you want to extract here> | cpio -idmv -D <insert where you want the extracted RPM file to go>
```
*# this will only extract the files within an RPM, it does not extract the SPEC file*

### Extract the scripts from a RPM file ###

```console
rpm -qp --scripts <insert the RPM file here> > <insert the output location of the script here>
```
*# this will only extract the pre-install and post-install scripts*

---
