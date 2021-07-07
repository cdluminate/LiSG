==========================
LiSG: Linux Survival Guide
==========================

:Author: Copyright (C) 2020-2021, Mo Zhou ``<lumin@debian.org>``
:Date: June 2021

.. contents::
   :depth: 3
..

This document is released under the ``AGPL-v3.0`` license.

Introduction
============

Different from commercial operating systems such as Microsoft Windows, the free
and open-source Linux operating system does not have any united official user
guide. Built upon the Linux kernel, different Linux distributions have very
distinct styles and mechanisms for assembling free and open-source software
from various sources, which eventually lead to fragmented pieces of knowledge
scattered across everywhere. Besides, the Linux world is also quickly evolving
with new tools and technologies, introducing yet more knowledge fragments.

In order to become an advanced user, one has to catch the "invariance" of Linux
during its evolving process, as well as build up a Linux knowledge network.
Thus, this document will try to interpret such "invariance" and "Linux
knowledge network" instead of duplicating materials you can see from other
Linux books. Namely, we are going to point out some "meta" knowledge such as
how to learn to use any tool that you are not familiar with.

This document mainly consists of three parts: (1) fundamental skills; (2)
having some fun with Linux; (3) Linux distribution development. For contents
like "what Linux is", "the history of UNIX and Linux", "what GNU is", please
refer to other materials.

The author appreciates the UNIX philosophy and free software (following GNU's
definition).  The author wishes that this document can help the reader
understand some details of Linux and have fun with it, instead of struggling
under Linux.

There may some some discrepancies in the document. Please open issue on Github
and point it out. That would be much appreciated. Moreover, suggestions are
welcome.

Conventions
-----------

1. shell command notation
1. manpage notation
1. coding style

Fundamental Survival Skills Under Linux
=======================================

Principals
----------

1. carefully read the screen output
2. ask smart questions

The Art of Command Line Interaction
-----------------------------------

*Where there is a shell, there is a way.*

Command line: resilient and robust, high availability, sometimes efficient.

How command line works
~~~~~~~~~~~~~~~~~~~~~~

::

    #include <stdio.h>
    int
    main(int argc, char** argv, char** envp) {
        printf("Hello, world!\n");
        return 0;
    }

Command line skills
~~~~~~~~~~~~~~~~~~~

Helps and Tips
~~~~~~~~~~~~~~

manpages

tldr

seeking for right tools

POSIX Standard
--------------

system interface

posix shell

Commonly used Toolbox
---------------------

Troubleshooting
---------------

Compiled Binary Programs and Shared Objects
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

readelf, ldd, objdump disassembly

Interpreted Scripts
~~~~~~~~~~~~~~~~~~~

Static Analysis
~~~~~~~~~~~~~~~

Dynamic Tracing
~~~~~~~~~~~~~~~

strace, gdb

Conventions
-----------

Having Fun with Linux
=====================

File Management and Processing
------------------------------

1. File Recognition
2. Archiving and Compression
3. Backup
4. Version Control
5. Encryption
6. Text Processing 

Storage System
--------------

Network and Server
------------------

1. Firewall (+endlessh)
2. Cluster
3. Networking (route, etc)
4. Downloading
5. Web Server
6. DNS Server

File Transmission and Remote Access
-----------------------------------

1. Between two hosts
2. Among multiple hosts
3. SSH
4. Tmux and Mosh
5. Casting Screen Output
6. Nohup

Workflow and Batched Jobs
-------------------------

Git
shell job control

Virtualisation and Containers
-----------------------------

Kernel Tricks
-------------

Tmpfs, sysrq, nice, etc

Domain Specific Applications
----------------------------

1. Production suites
2. Multimedia 
3. Scientific Computing
4. hardware acceleration
5. init program

Booting Linux
-------------

Linux Installation
------------------

1. example: root on USB
2. example: ext4 lvm2 luks
3. Software installation

Linux Distribution Development
==============================

May involve the Debian family (incl. Ubuntu), the Red Hat family (incl. Fedora),
the Gentoo and ArchLinux.

Linux Distribution Maintenance
------------------------------

Core Packages
~~~~~~~~~~~~~

Dependency Tree
~~~~~~~~~~~~~~~

This is where a distribution can be made more robust.

Package Management Systems
~~~~~~~~~~~~~~~~~~~~~~~~~~

Building Packages
~~~~~~~~~~~~~~~~~

Linux From Scratch
------------------

How to Participate
------------------

Mail Convention
~~~~~~~~~~~~~~~

LKML?

Volunteer Work
~~~~~~~~~~~~~~

+implications.

Further Reading
===============

[1] Eric S. Raymond, The Art of UNIX Programming. (TAOUP)
[2] Advanced Programming in UNIX Environment (APUE)
[2] UNP
[3] CSAPP
[4] KR C
[5] TAOCP
