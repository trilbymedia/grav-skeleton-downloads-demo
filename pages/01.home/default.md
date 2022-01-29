---
title: Home
body_classes: 'title-center title-h1h2'
---

# Downloads Pro
## Premium Plugin Demo

This is a demo site for [Downloads Pro](https://getgrav.org/premium/downloads-pro?target=_blank) based on Quark theme. Throughout the site we have highlighted numerous ways **Downloads Pro** can be used by either `downloads` page types and through [raw]`[download /]`[/raw] and [raw]`[downloads /]`[/raw] **shortcodes**.

[div class="text-center"]
[[fa icon="globe" /] Website](https://getgrav.org/premium/downloads-pro?target=_blank&classes=btn) 
[[fa icon="book" /] Documentation](https://getgrav.org/premium/downloads-pro/docs?target=_blank&classes=btn)
[[fa icon="github" /] Get This Demo](https://github.com/trilbymedia/grav-skeleton-downloads-demo?target=_blank&classes=btn)
[/div]

## Structure of the Site
This [skeleton [fa icon="external-link" /]](https://github.com/trilbymedia/grav-skeleton-downloads-demo?target=_blank) features a [Downloads](/downloads) page that we organized in a nested structure, to showcase how you can organize different categories in different Grav pages.

To demonstrate the powerful access level integration with Grav, we created a **Protected** category page that will require a proper authenticated user in order to be accessed. Additionally, we also included individual _protected_ assets in areas that are public. These assets will require user authentication. 

## You are in control

Shortcodes in Downloads Pro serve an important role and provide a powerful mechanism to integrate downloads anywhere on your site, wherever you can place content.

For example, to embed the downloads as we see them in the dedicated [Downloads](/downloads) page, we can use the [raw]`[downloads /]`[/raw] shortcode with the layout `list-folders`.

[prism classes="language-bbcode"]
[raw]
[downloads route="/downloads" layout="list-folders" /]
[/raw]
[/prism]

[downloads route="/downloads" layout="list-folders"]

## Embed Individual Downloads

 Downloads Pro comes with various built-in layouts that can be utilized with your content. Layouts can be also easily created to satisfy any need. More about layouts can be found in the [documentation](https://getgrav.org/premium/downloads-pro/docs?target=_blank).

### Button Layout
This layout renders a button with a customizable title that can be clicked to download the asset. Because it renders as an `<A>` tag, this particular layout can be also used inline with your content, if needed.

[prism classes="language-bbcode"]
[raw]
[download="/downloads/photos/nature/miroslav-skopek-4c82fCful4c-unsplash.jpg" title="Download Nature Photo" layout="button" /]
[download filename="harold-wainwright-Bqip9io1wgg-unsplash.jpg" route="/downloads/photos/urban" title="Download Urban Photo" layout="button" /]
[download filename="/downloads/photos/people/windows-wpIYy2lZ04s-unsplash.jpg" title="Download People Photo" layout="button" /]
[/raw]
[/prism]

[div style="display: flex;justify-content: space-between;"]
[download="/downloads/photos/nature/miroslav-skopek-4c82fCful4c-unsplash.jpg" title="Download Nature Photo" layout="button" /]
[download filename="harold-wainwright-Bqip9io1wgg-unsplash.jpg" route="/downloads/photos/urban" title="Download Urban Photo" layout="button" /]
[download filename="/downloads/photos/people/windows-wpIYy2lZ04s-unsplash.jpg" title="Download People Photo" layout="button" /]

! The file value has been specified in 3 different ways, they are all equivalent.

### Card Layout
[div class="d-flex"]
[div style="flex-shrink: 0;margin-right: 1rem;"]
[download filename="/downloads/photos/nature/miroslav-skopek-4c82fCful4c-unsplash.jpg" layout="card" width="300" /]
[/div]

[div class="ml-2" style="overflow: auto"]
#### Simple and beautiful
The `card` layout is a great way to present a download in a modern and appealing way. It can be placed inline, like in this example to blend nicely with your content.

Adding a card to your content can be done through the `download` shortcode, as you can see from the sample below:

[prism classes="language-bbcode"]
[raw]
[download filename="/downloads/photos/nature/miroslav-skopek-4c82fCful4c-unsplash.jpg" layout="card" width="300" /]
[/raw]
[/prism]
[/div]
[/div]


## Embedded Grid and Table Downloads
Finally, you can also embed a full list of downloads. *Downloads Pro* provides 2 layouts for this, `list` and `grid`. By default these layouts will also include the folders' navigation. Most likely this is not something expected when embedding, for that you can use the targeted layout version: `list-files` and `grid-files`.

! Note that the [Photos / Urban](/photos/urban) page, has a protected asset *lawless-capture (protected example)*, which you will only be able by [logging in](/sign-in).

### Cards Grid Layout
An example of a grid layout in use. Which is a replica of the [Photos / Urban](/photos/urban) section of this skeleton.

[prism classes="language-bbcode"]
[raw]
[downloads route="/downloads/photos/urban" layout="grid-files" width="300" /]
[/raw]
[/prism]

[downloads route="/downloads/photos/urban" layout="grid-files" width="300" /]


### Table List Layout
Now let's look at the same Grid example above, this time by using the `list-files` layout.

[prism classes="language-bbcode"]
[raw]
[downloads route="/downloads/photos/urban" layout="list-files" width="300" /]
[/raw]
[/prism]

[downloads route="/downloads/photos/urban" layout="list-files" width="300" /]