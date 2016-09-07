---
author: sboss
comments: false
date: 2016-08-16
layout: post
title: Reduxio storage
categories: review
tags:
- Reduxio
- storage
- no-snapshots
- no-replication
- startup
---

## Reduxio storage is forever-snapshots.

I met some friends that work at [Reduxio]( http://reduxio.com ) for a briefing on what Reduxio (as in product) is.  What the product does today is impressive for a startup.  And the information that I got about what is coming *soon* (all under **NDA** so don't ask!) makes it even more impressive.  Now since I have not placed my hands on the hardware yet, and beat it with the *storage monkey stick*(TM), I cant tell if what I was told is what is the truth.  Not that I don't believe them but when working for a startup, you tend to drink *the Koolaid* and believe all the hype.

**pros**
- HTML5 (only) UI.  No *bleeping* Java or Flash!
- No tweaking knobs.  It tweaks itself and humans can't try to *out think it*.
- very simple to setup/install (still **TBD**, but from what I can tell it is true).
- no snapshots. but you can roll an "disk" back to any point in time you wish.

**cons**
- **startup**. are they going to be here in 2 years or 5 years?
- very limited on configuration options. (also a pro).
- No active/active volumes.  Think in a *Metro Cluster* like using a **VPLEX**.
- no replication.
- no cloud tiering options.

I want to get my hands on some hardware and beat on it. I think it could be an awesome box.  Is it perfect? never. Is it ready for *Big Business* or Enterprise? nope.  But it is ready for the Small to Medium sized ones.
