---
layout: post
title: "Dirty Git Directories"
date: 2011-08-07 03:52
comments: true
categories: git bash
---
At my work, I still live in the world of Subversion. Nevertheless, I am able to use git by taking advantage of "git svn" which clones existing SVN repo's locally. It works great.

Unfortunately, my setup is not optimal. I have a bunch of git repo's, one for each SVN project. My future plans involve cloning at a higher level so I can have few git repo's. Until I fix that, I find it difficult to determine which repo's are "dirty".

Fortunately, I found Matthew McCullough's <a href="https://github.com/matthewmccullough/scripts/blob/master/finddirtygit">great script</a> solves this problem for me. For my setup, that just meant saving this script to the root of my project where all my git repo's reside. Then make the script executable. Voila!

<script src="https://gist.github.com/1109954.js?file=finddirtygit.sh"></script>

