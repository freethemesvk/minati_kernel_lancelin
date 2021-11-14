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



Powered by c4md.

COMPILED WITH GITPOD!
How to open workspace?
	Open gitpod.io/#https://github.com/freethemesvk/minati_kernel_lancelin
	It's your ide for developing kernel now.

How to compile:
	1. sudo su
	2. cd /workspace/minati_kernel_lancelin
	3. chmod +x compile/install compile/build
	4. apt install dos2unix && dos2unix compile/install compile/build
	5. ./compile/install
	It's will install compile dependencies
	6. ./compile/build
	It's will build kernel

GOOD LUCK

by c4md 2021©