---
layout: post
title: "Installing Ubuntu 11.10"
date: 2011-11-23 16:39
comments: true
categories: 
---

Handling driver troubles:

    # Adding following line to /etc/modprobe.d/blacklist.conf
    blacklist rt2800pci
    # Adding following lines to /etc/rc.local
    modprobe rt2800usb
    echo 2019 ed14 > /sys/bus/usb/drivers/rt2800usb/new_id

Installed many packages...

What I want are basically: some terminal (which is pre-installed), 
Emacs and Chrome. In addition to that, I need some development setup
like rvm etc. But there are many dependencies for that. 

For me, introducing [el-get](https://github.com/dimitri/el-get) and 
giving up SKK is a huge progress. 
But there are hidden dependency to emacs packages.

 * subversion, cvs, texinfo

[RVM](http://beginrescueend.com/) Also has its own hidden dependency.
But it shows the installation instruction at the last step.
That is great. 
