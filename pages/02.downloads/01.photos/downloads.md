---
title: Photos
downloads:
    include_all: true
    layout: 'grid'
    options:
        show_version: false
        hot: 20
---

  # Downloads
  Dictum hendrerit curae faucibus volute
  
  [downloads layout="grid" /]
  
  ## Instructions
  Scelerisque vestibulum ornare himenaeos a 
  hendrerit eros quisque, urna ultrices id 
  pellentesque nullam ultricies proin.
  
  Orci efficitur nunc parturient interdum.


## How does the frontmatter look like?

[prism classes="language-yaml"]
title: Photos
downloads:
  include_all: true
  layout: 'grid'
  options:
    show_version: false
    hot: 20
[/prism]

!!! This **parent page** sets the `grid` layout for itself and all its children. It also disables the `show_version` option and sets the `hot` tag to 20 days. These settings will be inherited by this page children.