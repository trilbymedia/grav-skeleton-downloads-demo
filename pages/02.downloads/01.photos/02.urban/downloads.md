---
menu: Urban
title: 'Urban Photos'
downloads:
  include_all: true
  info:
    -
      file: harold-wainwright-Bqip9io1wgg-unsplash.jpg
      enabled: true
      name: null
      featured: true
      download_name: null
      access: null
      version: null
    -
      file: lawless-capture-CWxzgiBUFb0-unsplash.jpg
      enabled: true
      name: 'lawless-capture (protected example)'
      featured: false
      download_name: protected.jpg
      access: site.login
      version: null
---

# Urban Photos

[downloads/]

[div style="margin-top: 2rem; font-size: 80%; text-align: right; font-style: italic;"]
Source: [unsplash](https://unsplash.com/?target=_blank)
[/div]

## How does the frontmatter look?

[prism classes="language-yaml"]
menu: Urban
title: 'Urban Photos'
downloads:
  include_all: true
  info:
    -
      file: harold-wainwright-Bqip9io1wgg-unsplash.jpg
      enabled: true
      name: null
      featured: true
      download_name: null
      access: null
      version: null
    -
      file: lawless-capture-CWxzgiBUFb0-unsplash.jpg
      enabled: true
      name: 'lawless-capture (protected example)'
      featured: false
      download_name: protected.jpg
      access: site.login
      version: null
[/prism]

!!! This page overrides the file `harold-wainwright-Bqip9io1wgg-unsplash.jpg` and marks it as **featured**.  
!!! Additionally, this page holds a protected asset `lawless-capture-CWxzgiBUFb0-unsplash.jpg` that you won't be able to see and download, unless you are [signed in](/sign-in) (`access: site.login`).
!!!
!!! Note also how we are customizing the **display name** to `laweless-capture (protected example)` as well as the **download name** to `protected.jpg`

! Note that because the parent page [Photos](../) is set to use layout `grid`, we don't need to specify it in this page. It will be inherited automatically.