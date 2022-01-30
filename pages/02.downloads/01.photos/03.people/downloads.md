---
menu: People
title: 'People in Photos'
downloads:
  include_all: true
  options:
    show_version: true
  info:
    -
      file: windows-wpIYy2lZ04s-unsplash.jpg
      enabled: true
      name: 'Custom name'
      featured: false
      download_name: null
      access: null
      version: 1.1.0
---

# People in Photos

[downloads/]

[div style="margin-top: 2rem; font-size: 80%; text-align: right; font-style: italic;"]
Source: [unsplash](https://unsplash.com/?target=_blank)
[/div]


## How does the frontmatter look like?

[prism classes="language-yaml"]
title: 'People in Photos'
downloads:
  include_all: true
  options:
    show_version: true
  info:
    -
      file: windows-wpIYy2lZ04s-unsplash.jpg
      enabled: true
      name: 'Custom name'
      featured: false
      download_name: null
      access: null
      version: 1.1.0
[/prism]


!!! This page overrides the file `windows-wpIYy2lZ04s-unsplash.jpg` and customizes its name to 'Custom name' and adds a version `1.1.0` to it.  
!!! Additionally, this page deviates from the parent by specifically enabling the `show_version` option. This in return will let the card display  the version for **Custom name**.

! Note that because the parent page [Photos](../) is set to use layout `grid`, we don't need to specify it in this page. It will be inherited automatically.