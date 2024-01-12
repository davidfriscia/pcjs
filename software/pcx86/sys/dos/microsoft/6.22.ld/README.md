---
layout: page
title: "MS-DOS 6.22 installed on large disk"
permalink: /software/pcx86/sys/dos/microsoft/6.22.ld/
machines:
  - id: deskpro386
    type: pcx86
    config: /machines/pcx86/compaq/deskpro386/vga/4096kb/machine.xml
    drives: '[{name:"68Mb Hard Disk",type:4,path:"/mylocaldisks/msdos_6_22_ld.json"}]'
    autoMount:
      A:
        name: None
      B:
        name: None
---

Work in progress

{% include machine.html id="deskpro386" %}
