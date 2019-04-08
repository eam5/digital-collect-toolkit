---
layout: default
title: Social Media Tools
nav_order: 5
has_children: true
permalink: /docs/social-media
---

# Tools for Archiving Social Media

This guide presents methods of collecting twitter data using tools built by [DocNow](https://www.docnow.io/), a collaborative effort between Shift Design, Inc., the University of Maryland, and the University of Virginia, with funding from the Andrew W. Mellon Foundation. We use the tools developed by DocNow for collecting twitter data because of their strong commitment to prioritizing ethical practices in collection, use, and preservation of social media content.
{: .fs-5 .fw-300 }

The following documentation is intended to assist in setting up [Twarc](https://github.com/DocNow/twarc), a DocNow tool for archiving twitter data. For more information on Twarc or other DocNow tools, please visit their [site](https://www.docnow.io/).
{: .fs-5 .fw-300 }

## Twarc for Twitter Data Collection

[Twarc](https://github.com/DocNow/twarc) is a command line tool that downloads tweets using Twitter’s API. API’s, or application programming interfaces, are simply ways that different organizations, whether it is Twitter or the Census bureau, provide more direct access to data. API’s also oftentimes provide limits to how much data you can gather. Twitter’s API limit for downloading tweets from a user account as of writing this is 3200 tweets. Twarc will handle Twitter API's [rate limits](https://developer.twitter.com/en/docs/basics/rate-limiting) for you.


The following pages provide instructions on installing and using Twarc. Parts of this guide are subject to change with updates to Twitter's developers site, so please use this guide as a general guideline. For troubleshooting with Twarc, please contact the developers of [DocNow](https://www.docnow.io/), and join their community of scholars, students, and archivists.

To get started you will need a [twitter account to register a twitter application](../social-media/twitter-setup/). Twarc also requires [Python](https://www.python.org/downloads/). 