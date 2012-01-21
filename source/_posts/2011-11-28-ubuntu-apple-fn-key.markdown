---
layout: post
title: "Ubuntu: Apple Fn Key, Guake"
date: 2011-11-28 21:48
comments: true
categories: computer
---

A friend of mine told me about [Guake](http://guake.org/).
I'm playing with this.

To make it useful, I need to change my keyboard setting.
See: https://help.ubuntu.com/community/AppleKeyboard

    # Add this to /etc/rc.local
    echo 2 > /sys/module/hid_apple/parameters/fnmode