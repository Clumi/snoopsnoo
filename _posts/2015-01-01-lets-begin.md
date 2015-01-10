---
layout: post
title: "Let's begin."
description: ""
category: 
tags: []
---
{% include JB/setup %}

Hello, and welcome to **SNOOP <i class="fa fa-search purple"></i> SNOO**'s development blog. I've been on reddit since its inception way back in 2005 (mostly lurking, though) and have always thought it would be interesting to analyze the massive amounts of data it generates, especially after its huge growth in the past few years – so I built **SNOOP <i class="fa fa-search purple"></i> SNOO**.

As of today, it simply does two things:

* Aggregate your reddit submissions and comments, and graphically display resulting data.
* Parse text in your comments and submissions, and extract relevant and potentially interesting information.


I built the web app in about three weeks, but I've been working on its NLP components for a couple of months now. I'm still new to NLP and as I try to wrap my head around it, results may often be erratic. 

The site is built on [Flask](http://flask.pocoo.org/) and hosted on the [Google Cloud Platform](https://cloud.google.com/). Charts are generated using [D3.js](http://d3js.org/). The NLP component is built on [TextBlob](https://github.com/sloria/TextBlob) and [NLTK](http://www.nltk.org/), and is hosted on [Blockspring](https://www.blockspring.com/).


I plan to update this blog regularly as the site evolves. Really. I've even made a New Year's resolution and everything.