---
layout: post
title: Anti anti-scraping tech
tags:
  - scraping
  - tech
---

#Motivation

My better half has a side-hustle re-selling products overseas, and recently opined about spending non-trivial amounts of time keeping tabs on some sites with frequent changes in product availability.

Being a software engineer, my first thought was to automate the process by building a scraper.

It wasn't as easy as I thought ( when is anything ever!). A `GET` request returned some code which suggests fingerprinting/anti-scraping tech. I decided to investigate.

[<img src="{{ site.baseurl }}/images/fp.jpg" alt="Whaat"/>{: .center-image}]
