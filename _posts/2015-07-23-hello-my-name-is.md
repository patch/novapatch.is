---
title: 'Hello, my name is __________.'
layout: post
permalink: /talks/hello-my-name-is/
category: coding
tags:
  - names
  - identity
  - unicode
  - i18n
---

I recently presented this new talk *Hello, my name is __________* on
supporting diverse user identities at [OSCON](http://www.oscon.com/), [Open
Source Bridge](http://opensourcebridge.org/), and
[YAPC::NA](http://www.yapcna.org/). Here is the video, slides, notes, and
additional resources.

### Video

Here’s the [video from Open Source
Bridge](https://www.youtube.com/watch?v=RqB2P5SPfgM). The earlier [video from
YAPC::NA](https://www.youtube.com/watch?v=SKbqCB2NPXw) is also available.

<iframe src="https://www.youtube.com/embed/RqB2P5SPfgM?feature=oembed"
width="560" height="315" frameborder="0" allowfullscreen="true"></iframe>

### Slides

Here’s the [latest version of the
slides](https://speakerdeck.com/patch/hello-my-name-is), as presented at OSCON.

<iframe src="https://speakerdeck.com/player/ef70b3970e9d4effa65affbe6ef03bca"
id="talk_frame_302715" width="560" height="378" frameborder="0"
allowfullscreen="true" allowtransparency="true" mozallowfullscreen="true"
webkitallowfullscreen="true"
style="border:0; padding:0; margin:0; background:transparent"></iframe>

### Description

Our personal identity is core to how we perceive ourselves and wish to be seen.
All too often, however, applications, databases, and user interfaces are not
designed to fully support the diversity of names expressed both locally and
internationally. This talk demonstrates ways to build applications that respect
users’ identities instead of limiting them.

Topics include:

 * Input, validation, storage, and display of personal names
 * Unicode usernames and solutions to security concerns
 * Internationalization and localization considerations

Although names provide a powerful example and are the focus of this
presentation, much of the topic is relevant to all types of user input. The
intended audience includes programmers, UX designers, and QA testers. Together
we can build inclusive software that supports diverse identities.

### Resources

#### My Open Source Projects
 * [i18n Testing Data](https://github.com/patch/i18n-testing)
 * [Unicode Programming Examples](https://github.com/patch/unicode-programming)

#### More about Names
 * [Personal Names around the
   World](http://www.w3.org/International/questions/qa-personal-names)
 * [Falsehoods Programmers Believe about
   Names](http://www.kalzumeus.com/2010/06/17/falsehoods-programmers-believe-about-names/)

#### Non-BMP Characters
 * [2015 Top Ten List: Why Support Beyond-BMP Code
   Points?](http://blogs.adobe.com/CCJKType/files/2015/02/beyond-bmp-top10-2015.pdf)
   <span style="font-size: 80%">[PDF]</span>
 * [Unicode Supplementary Characters Test
   Data](http://www.i18nguy.com/unicode/supplementary-test.html)
 * [How to Support Full Unicode in MySQL
   Databases](https://mathiasbynens.be/notes/mysql-utf8mb4)
 * [JavaScript Has a Unicode
   Problem](https://mathiasbynens.be/notes/javascript-unicode)

#### Unicode Usernames
 * [Unicode Identifier and Pattern Syntax](http://unicode.org/reports/tr31/)
 * [Unicode Security FAQ](http://unicode.org/faq/security.html)
 * [Unicode Security Considerations](http://unicode.org/reports/tr36/)
 * [Unicode Security Mechanisms](http://unicode.org/reports/tr39/)

<blockquote class="twitter-tweet" data-cards="hidden" lang="en"><p lang="en" dir="ltr">&quot;Preventing fake names is not worth discriminating against real users.&quot; —{% include twitter.html %} Excellent resources at <a href="https://t.co/59Wl7qcMxl">https://t.co/59Wl7qcMxl</a>. <a href="https://twitter.com/hashtag/osb15?src=hash">#osb15</a></p>&mdash; fureigh (@fureigh) <a href="https://twitter.com/fureigh/status/613467939476365312">June 23, 2015</a></blockquote>
<script async src="//platform.twitter.com/widgets.js" charset="utf-8"></script>

Thanks to everyone who participated in the session and discussion!