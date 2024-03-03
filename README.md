Intel MPSS 3.8.6 for Ubuntu 20.04 LTS
======================================

This repository contains Intel MPSS 3.8.6 modules. The source is patched to work
with Linux Kernel 5.4.0, it was only tested on Ubuntu 22.04, but should work
on any distro with the same kernel.

Requirements
------------

Before building the kernel modules, make sure you have all tools necessary to
build the Linux Kernel (e.g., GCC, Make, etc.) and the kernel source or
headers. On Ubuntu 22.04, should be enough to have the following packages
installed:

* build-essential
* linux-headers-generic

Building and Installing
-----------------------

To build, simply run make:

`$ make MIC_CARD_ARCH=k1om`

To install, you must be logged in as root or use sudo:

`# make install`

`$ sudo make install`
