---
title: "When to Use Static Generation v.s. Server-side Rendering"
description: "We recommend using **Static Generation** (with and without data) whenever possible because your page can be built once and served by CDN, which makes it much faster than"
date: "2020-02-01"
# socialImage: "../public/images/button-ui.png"
socialImage: "https://i.imgur.com/BGRReNJ.png"
---

We recommend using **Static Generation** (with and without data) whenever possible because your page can be built once and served by CDN, which makes it much faster than having a server render the page on every request.

You can use Static Generation for many types of pages, including:

- Marketing pages
- Blog posts
- E-commerce product listings
- Help and documentation

```javascript
// This is commented code
const x = "hello";
const y = (props) => {
  return props;
};
[Text you want to see](http://url-goes-here.com)

```

You should ask `yourself`: "Can I pre-render this page **ahead** of a user's request?" If the answer is yes, then you should choose Static Generation.

On the other hand, Static Generation is **not** a good idea if you cannot pre-render a page ahead of a user's request. Maybe your page shows frequently updated data, and the page content changes on every request.

In that case, you can use **Server-Side Rendering**. It will be slower, but the pre-rendered page will always be up-to-date. Or you can skip pre-rendering and use client-side JavaScript to populate data.

- Prism: Lightweight, robust, elegant syntax highlighting
- MIT license http://www.opensource.org/licenses/mit-license.php/
- @author Lea Verou http://lea.verou.me
- Reach Lea at fake@email.com (no, not really)
- And this is a Markdown link. Sweet, huh?
  \*/
  var foo = 5;
  (hello)[http://google.com]
