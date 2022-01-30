---
menu: Protected
title: 'Protected by Login'
access:
    site.login: true
downloads:
    layout: grid
    include_all: true
    info:
        -
            file: file_example_MP3_1MG.mp3
            enabled: true
            name: null
            featured: true
            download_name: null
            access: null
            version: null
---

# Protected by Login

[downloads /]

## How does the frontmatter look like?

[prism classes="language-yaml"]
menu: Protected
title: 'Protected by Login'
access:
  site.login: true
downloads:
  layout: grid
  include_all: true
  info:
    -
      file: file_example_MP3_1MG.mp3
      enabled: true
      name: null
      featured: true
      download_name: null
      access: null
      version: null
[/prism]

!!! This **page** is protected and requires `site.login` permissions to be reached. The page also sets the `grid` layout for its assets and overrides `file_example_MP3_1MG.mp3` to mark the asset as **featured**.