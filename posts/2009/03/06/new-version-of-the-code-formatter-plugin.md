---
title: New version of the Code Formatter Plugin
date: 2009-03-06
status: publish

author: stevedunn
excerpt: ''
type: post
id: 47
tags:
    - Uncategorised
tag: []
post_format: []
blogger_blog:
    - stevedunns.blogspot.com
blogger_author:
    - 'Steve Dunn'
blogger_permalink:
    - /2009/03/new-version-of-code-formatter-plugin.html
blogger_internal:
    - /feeds/32841709/posts/default/1615687804045075963
dsq_thread_id:
    - '6144385796'
---
Version 2.0 of the Code Formatter Plugin for [Windows Live Writer](http://download.live.com/writer) is now available.

New in this version is the ability to use different formatting engines – in this version: [ActiPro](http://www.actiprosoftware.com/Products/DotNet/WindowsForms/SyntaxEditor/Default.aspx) and [SyntaxHighlighter 2.0](http://code.google.com/p/syntaxhighlighter/)

Also new is the ability to output either formatted code as text or as a bitmap.

> A massive thank you to [ActiPro](http://www.actiprosoftware.com/Default.aspx) for donating the [ActiPro Syntax Editor](http://www.actiprosoftware.com/Products/DotNet/WindowsForms/SyntaxEditor/Default.aspx) component – **the** best code editor available!

If you’re reading this in an aggregator, the following code snippets may look unformatted (apart from the bitmap), but if you’re not, then it should be all nicely formatted.

Here’s some output from ActiPro as text:

<span>
<pre style="background-color:#FFFFFF;;overflow: auto;"><span style="color: #0000FF;">public</span><span style="color: #000000;"> </span><span style="color: #0000FF;">int</span><span style="color: #000000;"> TabWidth
{
  </span><span style="color: #0000FF;">get</span><span style="color: #000000;">
  {
      </span><span style="color: #0000FF;">return</span><span style="color: #000000;"> _content.GetInt(</span><span style="color: #800000;">@"</span><span style="color: #800000;">TabWidth</span><span style="color: #800000;">"</span><span style="color: #000000;">, </span><span style="color: #800080;">4</span><span style="color: #000000;">);
  }
  </span><span style="color: #0000FF;">set</span><span style="color: #000000;">
  {
      _content.SetInt(</span><span style="color: #800000;">@"</span><span style="color: #800000;">TabWidth</span><span style="color: #800000;">"</span><span style="color: #000000;">, value);
  }
}
</span>

Here it is again as a bitmap:

[![image](/static/images/imported_from_wp/2009/03/image_thumb-5B3-5D.png "image")](/static/images/imported_from_wp/2009/03/image_thumb-5B3-5D.png)

and here it is using SyntaxHighlighter 2.0

```
public int TabWidth
{
  get
  {
      return _content.GetInt(@"TabWidth", 4);
  }
  set
  {
      _content.SetInt(@"TabWidth", value);
  }
}
```

[Please feel free to read more and download it.](https://sites.google.com/site/stevedunns/codeformatterforwindowslivewriter)