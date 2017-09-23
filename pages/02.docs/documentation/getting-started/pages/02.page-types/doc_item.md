---
title: 'Page types and extended pages'
routable: false
---

Grav natively supports 3 primary types of Pages that allows the creation of a rich selection of web content. TargetDummy extends this notion with secondary page types with inherited behaviors of the primaries. Those types are:

### Regular Page (primary page)

A regular Page is generally a single page such as a **blog post**, **contact form**, **error page** etc. This is the most common type of page that is created when only inline (non-parameterized block) content is required. By default a Page is considered a regular page unless you tell Grav otherwise.

#### Listing Page (primary page)

This is really an extension of a regular Page. This is a page that has a reference to a collection of pages.

The simplest approach to setting this up is to create **child-pages** below the Listing Page. An example of this would be a **blog listing page**, where you would display a summary list of blog posts that exist as child-pages.

There is also some configuration settings to **control the order** of the listing as well as a **limit on the number of items**, and whether or not **pagination** should be enabled.

!! A sample **Blog Skeleton** using a **Listing Page** can be found in the [Grav Downloads](https://getgrav.org/downloads/skeletons).

### Modular Page

A Modular Page is a special type of listing page because it actually builds a **single page** from its **child-pages**. This allows for the ability to build very complex **one-page layouts** from Modules. This is accomplished by constructing the **Modular Page** from multiple **Module-folders** found in the page's primary folder.

Each of these page types follow the same basic structure, so before we can get into the nitty-gritty of each type, we must explain how pages in Grav are constructed.

!! A Module, because it is intended to be part of another page, is inherently not a page you can reach directly via a URL. Because of this, all modular pages are by default set as **non-routable**.