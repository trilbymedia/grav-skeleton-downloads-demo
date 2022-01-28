---
title: Software
downloads:
  layout: list
  info:
    -
      file: grav-admin-v1.7.28.zip
      enabled: true
      name: null
      featured: false
      download_name: grav-admin.zip
      access: null
      version: 1.7.28
    -
      file: grav-v1.7.28.zip
      enabled: true
      name: null
      featured: true
      download_name: grav-core.zip
      access: null
      version: 1.7.28
    -
      file: mars-rover-manual-v5.3.7.tar.gz
      enabled: true
      name: null
      featured: false
      download_name: null
      access: null
      version: 16.13.2
    -
      file: node-v16.13.2-win-x64.zip
      enabled: true
      name: 'NodeJS for Windows (x64)'
      featured: false
      download_name: null
      access: null
      version: 16.13.2
---

# Software

[downloads /]

## How does the frontmatter look?

[prism classes="language-yaml"]
title: Software
downloads:
  layout: list
  info:
   -
    file: grav-admin-v1.7.28.zip
    enabled: true
    name: null
    featured: false
    download_name: grav-admin.zip
    access: null
    version: 1.7.28
  - 
    file: grav-v1.7.28.zip
    enabled: true
    name: null
    featured: true
    download_name: grav-core.zip
    access: null
    version: 1.7.28
  - 
    file: mars-rover-manual-v5.3.7.tar.gz
    enabled: true
    name: null
    featured: false
    download_name: null
    access: null
    version: 16.13.2
  - 
    file: node-v16.13.2-win-x64.zip
    enabled: true
    name: 'NodeJS for Windows (x64)'
    featured: false
    download_name: null
    access: null
    version: 16.13.2
[/prism]


!!!! Pay close attention to the file `mars-rover-manual-v5.3.7.tar.gz` and you will notice the custom thumbnail, how?  
!!!! This is possible because [Downloads Pro](https://getgrav.org/premium/downloads-pro?target=_blank) supports Grav's [Thumnail Location lookup](https://learn.getgrav.org/17/content/media?target=_blank#thumbnail-location).  
!!!! By uploading a thumbnail in the same location and with the name `mars-rover-manual-v5.3.7.tar.gz.thumb.jpg`, **Downloads Pro** will render that image instead of the default media extension one.

!!! This page utilizes a `list` layout and overrides multiple files to customize the assets **display name**, **download name** and to add the **version**. 