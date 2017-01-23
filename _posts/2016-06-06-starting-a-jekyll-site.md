---
layout: post
title:  "Steps to start a new Jekyll site without driving yourself insane"
date:   2016-06-06 08:03:10 -0500
categories: workflow
---

# workflow

## On github:
+ Make a repo for the site you want to build
+ Make a gh-pages branch in that repo and set it to default

## On your machine
+ clone that repo into a directory `git clone <url of that repo>`
+ cd to that directory
+ start a new jekyll site for that directory: `jekyll new . --force`
++ the force option allows it to not error out
+ create a CNAME file and put the hostname you want into it

## On your domain provider:
+ Create a CNAME record in your DNS zone file that points the hostname you want at <youraccountname>.github.io
+ Give that some time to propagate/take effect

## Back on your machine
+ Do the steps in the workflow post
