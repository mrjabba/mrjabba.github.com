---
layout: post
title: "All Your Rebase are Belong to Me"
date: 2011-08-10 19:39
comments: true
categories: bash
---
The more I play with bash functions, the more I realize how much I can automate my typing in Linux. Because we use git svn and clone each svn repo separately at work, it makes it difficult to move from trunk to branch and back again. I've solved directory navigation issues by installing [autojump](https://github.com/joelthelion/autojump/wiki "autojump"). However, I usually want to rebase all my projects each morning. And, I probably want trunk and the current release branch. This does that for me now.

{% gist 1138655 %}

*notify-send* is one of my favorite shell commands. I use this for other things too. For example, I can have it tell me when my build is done. I'd also like to create one to tail the JBoss log and tell me when JBoss is started. That way I can do other things while JBoss is starting.

I can improve on this. I need to learn how to make my functions more generic (just like my other code). This script assumes 2 symlinks at my root. That's fine. But, I should define those as variables. And, I should extract them to separate bash files and include them using the source command rather than just hacking my .bashrc file directly. One step at a time.
