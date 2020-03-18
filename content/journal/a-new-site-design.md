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

The motivation to change my site came from my desire to stop paying hosting
fees.  As part of researching how I would transition to a cloud host, I was
forced to look at my current site.  It was embarrasing that I hadn't made a
site update in 8 years.  Things were looking pretty old.

I ended up moving my hosting to
[Google Cloud Storage](https://cloud.google.com/storage) since there is a
permanent free tier that I felt I could fit into.

## Static Site Generation with Hugo

I've been interested in what are now called static site generators from almost
the very beginning of their existence.  My main motivation was that it felt
like having a full database for my dinky blog was overkill.  At the time, I
ended up going with a perl-based system called [Blosxom](http://blosxom.sourceforge.net/).

Since I last redesigned my site using Blosxom (in 2012 or so), the environment
of static site generators has blown up.  When I was looking to get off my
hosting provider, I looked at several static site generators and landed on
[Hugo](https://gohugo.io/) for the following reasons:
  - Extensive library of decent looking templates
  - Distributed as a single executable (Jekyll, for instance, requires a Ruby
    environment to be set up)
  - Written in [Go](https://golang.org/), which I don't know but I'm interested
    in.  I only know [Python](https://www.python.org/), and the only static
    site generator that I found using Python is
    [Pelican](https://blog.getpelican.com/), but their templates are not great.

So now I have a site up, generated with Hugo, hosted on the Google Cloud for
free.  Woot.
