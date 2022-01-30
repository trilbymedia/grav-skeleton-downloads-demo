---
title: Photos
downloads:
    include_all: true
    layout: 'grid'
    options:
        show_version: false
        hot: 20
---

# Photos

[downloads /]

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
!!!
!!! You will notice that, unlike other pages, this one specifically says "**No Downloads available**". That is because `grid` layout bundles both `list-folders` and `grid-files`. If we wanted to just list the folders, we could have used `list-folders`, instead.