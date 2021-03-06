---
title: "OpenSourcing"
categories: 
layout: "posts"
date: "2011-06-16 10:57:00"
updated: "2011-06-17 07:21:44"
blogger:
    siteid: "7706585097329252419"
    postid: "3250501138587112698"
---


I recently published my project, <a href="http://code.google.com/p/test-data-control">test-data-control</a>, on <a href="http://code.google.com/intl/no/projecthosting/">googlecode</a>, and want to jot down some stuff before I forget.
I wanted a subversion-enabled hosting, and chose Google because I have the impression they're fast and convenient pluss I like their <a href="http://code.google.com/p/support/wiki/MakingHostingBetter">philosophy</a>.
At <a href="http://code.google.com/p/support/wiki/GettingStarted">first</a>, I found that I had to choose a license and structure the project so that it goes nicely into Google. I had a little ponder, but chose <a href="http://www.apache.org/licenses/">Apache license</a> to go easy.
Filling in the form was straight forward, but I should have drafted it before I started on the web, these fields were filed:

Project name, summary, description, version control system, license and label(s)

**Gotcha**: Project name and version control system can not be changed later.
 
I then proceeded to apply for Sonatype OSS Maven Repository access, so that other projects can get to this library (they even push to Maven Central). Following the <a href="https://docs.sonatype.org/display/Repository/Sonatype+OSS+Maven+Repository+Usage+Guide">Usage guide</a>, I found I needed some more stuff, mainly in pom, and should change my groupId.

**Wisdom**: I should have known what it took before I first comitted project to Google, but it wasn't a big sweat.
 
All in all, the application processes were smooth and pleasan. Google project hosting was available immediately, Sonatype OSS Maven Repository access was ready for me over night (I'm on European timezone, so I guess they work when I sleep, which is a nice thought).
 
I was also surprised to experience a period of euphoria, having published something for the first time. I'd say it's worth the extra effort of preparing it and publishing it just for that feeling. Another nice thing I have experienced since I started sharing my ambitions with coworkers is that my status have increased so that I'm being used as an authority and pulled into discussions about related issues. I also get all kinds of tips now that they know I'm working on this thing. It feels like the project is starting to pull it's own weight.

The authority stamp feels a bit premature, because I feel that I need to produce a fully working system and prove it before I can claim that. I'm only glad that I did a fair bit of literature research before I came to this, so I'm usually able to answer and give some advise without making a fool of myself.
