---
title: "A New Site Design"
date: 2020-03-18
draft: false
tags: [
    "technology"
]
---
While the rest of the world is worrying about the COVID-19 global pandemic,
I decided to do a third redesign of my personal website.
<!--more-->

## Migration to Google Cloud Storage

I decided a few years ago I wanted to stop paying hosting fees.  Several places
had emerged where I could host for free or almost free.  I played around with
[AWS](https://aws.amazon.com/) and [GCP](https://cloud.google.com/).  Each
had free tiers where I could learn.  I ended up moving my hosting to
[Google Cloud Storage](https://cloud.google.com/storage) since there is a
permanent free tier and it tied in with my overall Google account.

While I was researching cloud hosts, I realized my current site was embarrasing.
I hadn't updated the thing in 8 years.  It was looking pretty shabby.

## Static Site Generation with Hugo

I've been interested in static site generators since before I did my last
redesign.  It always felt like having a full database (such as 
[Wordpress](https://wordpress.com/)) for my dinky blog was overkill.  When I did
my last redesign (in 2012 or so), I ended up going with a perl-based system
called [Blosxom](http://blosxom.sourceforge.net/).  I think Blosxom was one of
the first, if not THE first, static site generators.

Since then, the number of static site generators has blown up.  Now 
they have a cool new name ([JAMstack](https://jamstack.org/)).  When I was
looking to get off my hosting provider, I looked at several static site
generators and landed on [Hugo](https://gohugo.io/) for the following reasons:
  - Extensive library of decent looking templates
  - Distributed as a single executable ([Jekyll](https://jekyllrb.com/),
    for instance, requires a Ruby environment to be set up)
  - Written in [Go](https://golang.org/), which I don't know but I'm interested
    in.  I only know [Python](https://www.python.org/), and the only static
    site generator that I found using Python is
    [Pelican](https://blog.getpelican.com/), but their templates are not great.

So now I have a site up, generated with Hugo, hosted on the Google Cloud for
free.  Woot.
