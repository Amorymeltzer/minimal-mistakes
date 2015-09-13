---
layout: post
title: Stately Astronauts
modified: 2015-09-10
categories: 
excerpt:
tags: [dataviz, r, space, astronauts, population]
image:
  feature:
date: 2015-05-10
---

I swear, this isn't going to be a "[dadviz uses bad heatmaps](/superbowl-calories)" blog.

Still, there was one more I couldn't pass up.  [@dadaviz](https://twitter.com/dadaviz) recently [posted](http://dadaviz.com/i/3797) the following map, showing how many astronauts came from each state:

![](/images/astronautMapOriginal.png)

Ignoring the weird shifts that take place when each state is an equal-area square and you still approximate a standard USA map, this suffers from the same population-based failings as that [famous xkcd heatmap](https://xkcd.com/1138/) implies.  Using the same basic technique as before, I created a population-adjusted map:

![](/images/astrosbystate.png)

Lighter colors correspond to more astronauts per state.  Midwestern states such as Iowa and the Dakotas as well as Colorado show up with the highest rates.  Strong engineering and military backgrounds?  That is an exploration for another day, but it's clear that population-adjusted maps paint a **very** different picture.
