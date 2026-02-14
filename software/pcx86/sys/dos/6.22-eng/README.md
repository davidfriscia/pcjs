---
layout: page
title: MS-DOS 6.22 English
permalink: /software/pcx86/sys/dos/6.22-eng/
redirect_from:
  - /disks/pcx86/windows/3.10/
  - /disks/pc/windows/3.10/
preview: images/screenshot.png
machines:
  - id: deskpro386
    type: pcx86
    config: /machines/pcx86/compaq/deskpro386/vga/4096kb/machine.xml
    drives: '[{name:"47Mb Hard Disk",type:5,path:"https://pcjs-img.dfri.info/pcx86/47mb/dos_622eng_47MB.json"}]'
    autoMount:
      A: "None"
      B: "None"
---

The PCjs machine below starts MS-DOS 6.22.

{% include machine.html id="deskpro386" %}
