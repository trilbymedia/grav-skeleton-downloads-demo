---
title: Home
body_classes: 'title-center title-h1h2'
downloads:
    enabled: false
---

# Downloads Pro
## Plugin Demo

For more information visit [Downloads Pro website](https://getgrav.org/premium/downloads-pro).

### Embedded Downloads

[downloads route="/downloads" layout="list-folders"/]

### Button Layout

[div style="display: flex;justify-content: space-between;"]
[download="/downloads/photos/nature/miroslav-skopek-4c82fCful4c-unsplash.jpg" title="Download Nature Photo" layout="button" /]
[download filename="harold-wainwright-Bqip9io1wgg-unsplash.jpg" route="/downloads/photos/urban" title="Download Urban Photo" layout="button" /]
[download filename="/downloads/photos/people/windows-wpIYy2lZ04s-unsplash.jpg" title="Download People Photo" layout="button" /]

### Card Layout
[download filename="/downloads/photos/nature/miroslav-skopek-4c82fCful4c-unsplash.jpg" layout="card" width="300" /]

### Cards Grid Layout
[downloads route="/downloads/photos/urban" layout="grid-files" width="300" /]