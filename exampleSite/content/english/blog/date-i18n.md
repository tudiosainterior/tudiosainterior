---
title: Como ser Alba
date: 2021-04-01T00:00:00.000+01:00
author: Amy Cohen
image: images/blog/blog-post-1.jpg
bg_image: "/images/img_9753.JPG"
categories:
- Technical Assistance
tags:
- How to
- Technology
type: post

---
To write out an [ISO 8601](https://en.wikipedia.org/wiki/ISO_8601) timestamp in the current language, you can use the `date_l10n` shortcode:

Writing

    {{%/* date_l10n "2020-10-20" */%}}

will result in

    {{% date_l10n "2020-10-20" %}}

You can optionally specify a different [formatting layout](https://gohugo.io/functions/dateformat/#datetime-formatting-layouts):

For example, the following

    {{%/* date_l10n "2020-10-20" ":date_short" */%}}

will result in

    {{% date_l10n "2020-10-20" ":date_short" %}}
    
    Hay que ser muy guapa