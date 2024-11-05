---
title: "Linux repo with missing grouplist"
date: 05-11-2024
---

## Requirements

- Redhat
- Centos
- Rocky
  
## How to manually install "Development Tools"

### Using YUM

```bash
sudo yum install -y autoconf automake binutils bison flex gcc gcc-c++ gdb glibc-devel libtool make pkgconf pkgconf-m4 pkgconf-pkg-config redhat-rpm-config rpm-build rpm-sign strace 

sudo yum install -y asciidoc byacc ctags diffstat elfutils-libelf-devel git intltool jna ltrace patchutilsperl-Fedora-VSP perl-Sys-Syslog perl-generators pesign source-highlight systemtap valgrind valgrind-devel

sudo yum install -y cmake expect rpmdevtools rpmlint
```

### Using DNF

```bash
sudo dnf install -y autoconf automake binutils bison flex gcc gcc-c++ gdb glibc-devel libtool make pkgconf pkgconf-m4 pkgconf-pkg-config redhat-rpm-config rpm-build rpm-sign strace 

sudo dnf install -y asciidoc byacc ctags diffstat elfutils-libelf-devel git intltool jna ltrace patchutilsperl-Fedora-VSP perl-Sys-Syslog perl-generators pesign source-highlight systemtap valgrind valgrind-devel

sudo dnf install -y cmake expect rpmdevtools rpmlint
```
