---
title: Converting System.Drawing.Color to HTML color (and vice-versa)
date: 2006-08-18
status: publish

author: stevedunn
excerpt: ''
type: post
id: 104
tags:
    - Uncategorised
tag: []
post_format: []
blogger_blog:
    - stevedunns.blogspot.com
blogger_author:
    - 'Steve Dunn'
blogger_permalink:
    - /2006/08/converting-systemdrawingcolor-to-html.html
blogger_internal:
    - /feeds/32841709/posts/default/115593693877402278
---
#####  

This is something I need very rarely. So rare in fact that in-between uses it is completely removed from my memory, leaving just the fact that I know I’ve searched for it before!

To convert a .NET Color object to an HTML RGB or named color, use

```
string colorAsString = ColorTranslator.ToHtml( _backgroundColor ) ;
```

and vice-versa

```
Color c = ColorTranslator.FromHtml( @"#RRGGBB" ) ;
```
