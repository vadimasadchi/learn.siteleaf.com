---
title: Liquid
date: 2015-10-31 20:03:00 -04:00
position: 2
---

Liquid is an open-source templating language that was developed by [Shopify](http://shopify.com). It uses tags, objects, and filters to render out content into a theme.

For an in-depth Liquid reference, check out the [official Liquid documentation](https://shopify.github.io/liquid/).
{: .tip}

### [Tags](http://shopify.github.io/liquid/tags/)

A tag is a piece of logic that will tell the templating engine what to do. This includes operations like `if`, `for`, `foreach`, and `capture`. For example:

Note that each tag is ended with the same tag, prepended with `end`.

### Objects

An object is a piece of data that has attributes with content. An object can be your site, a post, a set of posts, and so on. For example:

### [Filters](http://shopify.github.io/liquid/filters/)

Filters are used to modify the output of attributes (i.e., strings, numbers, variables, and objects):

---

### Further Reading

- [Shopify: Liquid documentation](https://shopify.github.io/liquid/)
- [Jekyll: Variables](http://jekyllrb.com/docs/variables/)
