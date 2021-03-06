---
title:  "IndieWeb"
date:   2017-04-23 23:00:00
description: Overview of support for IndieWeb formats.
---

Micro.blog supports several formats and protocols pioneered by the <a href="https://indieweb.org/">IndieWebCamp</a>. We also believe in many of the same principles — that owning your content matters, and that you should post to your own site first before cross-posting or replying on other social networks.

**Micropub:** Micro.blog for iOS can post to Micropub-compatible sites. The Micro.blog server also supports the Micropub API for posting from other clients like [Quill](https://quill.p3k.io/). See [posting APIs](/2017/api-posting/) for details.

**Webmention:** Replies in Micro.blog are sent as Webmentions to the target site if it supports Webmention. There is also limited support for receiving mentions from external blogs when they link to Micro.blog-hosted blogs.

**Microformats:** All hosted microblogs are marked up with Microformats. See the [feeds page](/2017/api-feeds/) for details.

**WebSub:** Micro.blog can subscribe to blogs using WebSub to receive real-time notifications for when a blog post is published.