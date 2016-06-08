---
author: sboss
comments: false
date: 2016-05-18
layout: post
title: infrastructure automation
categories: news
tags:
- infrastructure automation
- puppet
- anisble
- chef
- saltstack
---

## how do you automate your infrastructure?

after talking to my boss (ok I just violated the no work talk on the blog) about technologies that I would like to (re)learn and expand my knowledge base.  we both agreed that infrastructure automation (or whatever you want to call it) would be a good fit for me.  I have experience with both [chef]( http://chef.io ) and [puppet]( http://puppet.com ).

so a few years back I setup chef to automate the configuration at the house. it worked but I felt it was clunky.  it is a good product and works for some people.  just not me.

so I switched to puppet (OSS version) and it worked better for me.  and at the same time my employer (not my current one) was using the OSS version to control their infrastructure.  so I got more experience with it.  mostly copying other peoples manifests, then hacking at them until they worked for me.

while doing some consulting work (doesn't every SME do some consulting on the side?) I worked with [ansible]( http://anisble.com ). and it worked for them but I found it lacking. I know it has gotten better in the recent year+ but it is not as complete across platforms (server, storage, network, load balancers, firewalls, etc) as puppet is.

so I have started a journey to become a puppet master.  and I have a lot to learn as a lot has changed in the last few years. **A LOT**.  but I love to learn so it will be fun.

now my question for all y'all, is *what do you use to automate your infrastructure?*
