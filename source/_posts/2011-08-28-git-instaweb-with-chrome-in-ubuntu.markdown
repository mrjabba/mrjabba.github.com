---
layout: post
title: "Git Instaweb With Chrome in Ubuntu"
date: 2011-08-28 15:00
comments: true
categories: 
---

So you've discovered git [instaweb](http://manpages.ubuntu.com/manpages/intrepid/man1/git-instaweb.1.html "instaweb")?

But you want to use Chrome? It isn't supported. Ruh-roh. No worries. It's an easy fix. Open your .gitconfig directory in your user home directory. Add a Chrome section specifying the path to it. Then reference it in the instaweb section.

{% gist 1177146 %}

Happy browsing.
