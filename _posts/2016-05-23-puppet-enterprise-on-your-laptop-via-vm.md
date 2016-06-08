---
author: sboss
comments: false
date: 2016-05-23
layout: post
title: puppet enterprise on your laptop via vm
categories: news
tags:
- puppet
- puppet-enterprise
- laptop
- vm
---

## how to run PE on your laptop to do demos or testing with.

first one here is the components I am using. you don't have to mimic me but your instructions will differ.

* VMWare Workstation 12 (doesn't have to be 12 but that is what I have).  For Mac, use Fusion. it works just as well or better that Workstation.
* VM with 4gig of RAM, 20gig HD, and networking.
* Ubuntu 14-04 LTS (16-04 LTS is not supported yet and PE wont install on it - I tried it wont do it).
* Puppet Enterprise (PE) 2016.1

PE requires the puppet master to be in DNS as a FQDN (fully qualified domain name). and if you are working off a VM on your laptop then you don't have a valid FQDN.  **EEKS!**

dnsmasq to the rescue.  dnsmasq will respond to DNS requests but get its information out of the /etc/hosts file for a given domain.  so I named my vm *puppetmaster.storagemonkey.vm* with the domainname of *storagemonkey.vm*.  so whenever anything on that vm does a dns lookup for puppetmaster, it gets the IP address that is in the file.  this gets me past DNS lookup issue of PE.

simple fix for a simple but could be complicated issue.

now follow the standard PE install method.  the VM needs to be either NAT or BRIDGED mode because it will want to talk to the *mothership* and to fetch new packages via apt/yum.  I wont detail these steps as it is very well documented on the [puppet]( http://docs.puppet.com ) site.
