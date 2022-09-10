---
layout: blog
title: first blog test
description: this is test description
date: 2022-09-10T03:35:02.670Z
heroImage: /assets/blog/blog1.png
---
The last piece to our auth puzzle is some smooth handling of routes for authenticated users. For example, the *home* for an authenticated user might be the `/dashboard` page. For anyone else it is the index. How do we handle redirecting users to the best page without flashing multiple interfaces?

This is where that second cookie we set comes in. We'll inject a script tag with some redirect logic in the `<head/>` of our application. Handling redirections is now checking if that `authed` cookie is set and redirect to the appropriate page, something like so:

```

```

```js

```