---
author: sboss
comments: false
date: 2016-08-11
layout: post
title: Red Hat storage
categories: review
tags:
- Red Hat
- Gluster
- Ceph
- SDS
---

## Red Hat storage is all SDS.

Recently I have been looking at [Red Hat]( http://redhat.com ) storage.  It comes down to all of their offerings are Software Defined Storage (SDS).  Is that good or bad? neither.  Some people like hardware and software that is specific to a "storage platform".  Think the storage arrays that we all know and love.  Some have embraced the new model of SDS.  In SDS who care about the hardware, we will write code to get around any hardware issues or concerns.  Thus we can run on any hardware that meets certain specs.

[Gluster]( http://redhat.com/en/technologies/storage/gluster ) is the file based storage software that Red Hat bought a few years back.

[Ceph]( http://redhat.com/en/technologies/storage/ceph ) is the object store & block storage software that is designed and written by the community.  The community's [site]( http://ceph.com/ ) has a lot of good documentation especially related to the core technology.  Ceph is an object store that is optimized for things like [OpenStack]( http://www.openstack.org/ ).

Only time will tell if SDS on commodity hardware will take over the storage market or not.
