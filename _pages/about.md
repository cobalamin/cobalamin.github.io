---
permalink: /
title: "Simon Welker"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a first-year Computer Science PhD Student at [University of Hamburg](https://www.inf.uni-hamburg.de/en/inst/ab/sp/home.html) and the [Center for Free-Electron Lasers](https://cid.cfel.de) at [DESY](https://desy.de), supervised by Prof. [Timo Gerkmann](https://www.inf.uni-hamburg.de/en/inst/ab/sp/people/gerkmann.html) and Prof. [Henry Chapman](https://cid.cfel.de/team/henry_chapman/). My project is part of the [Helmholtz graduate school DASHH](https://www.dashh.org/).

My research focuses on solving inverse problems that arise in the fields of X-ray imaging and speech processing, especially the problem of *Phase Retrieval*. I aim to find and exploit common ground between both fields of research by viewing these problems through the common lens of signal processing, and to develop novel methods based on both deep learning and classical nonlinear optimization. Currently, I am working on adapting and extending *generative diffusion models* in order to make solving inverse problems easier with effective generative priors. I am especially interested in the recent topic of [Scientific Machine Learning](http://www.stochasticlifestyle.com/the-essential-tools-of-scientific-machine-learning-scientific-ml/) and the [confluence of deep learning and differential equations](https://dlde-2022.github.io/).

Besides my academic studies, I am also a trained software developer and [have worked in the industry for 5+ years](/cv/). I always strive to develop my research code using best practices from my experience in software engineering.


Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
