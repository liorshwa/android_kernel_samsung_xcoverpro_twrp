## Official Kernel Source SM-G715FN_QQ_Opensource_G715FNXXS6ATI1

Linux kernel
============

This file was moved to Documentation/admin-guide/README.rst

Please notice that there are several guides for kernel developers and users.
These guides can be rendered in a number of formats, like HTML and PDF.

In order to build the documentation, use ``make htmldocs`` or
``make pdfdocs``.

There are various text files in the Documentation/ subdirectory,
several of them using the Restructured Text markup notation.
See Documentation/00-INDEX for a list of what is contained in each file.

Please read the Documentation/process/changes.rst file, as it contains the
requirements for building and running the kernel, and information about
the problems which may result by upgrading your kernel.

## How to compile :

```sh
export ANDROID_MAJOR_VERSION=q
export ARCH=arm64
make exynos9610-xcoverproxx_defconfig
make -j24
