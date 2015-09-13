---
layout: post
title: Superbowl Calories
modified: 2015-09-09
categories: 
excerpt:
tags: [dataviz, r, sports, football, food, population]
image:
  feature:
date: 2015-02-02
---
Yesterday was the Super Bowl, and the Seattle Seahawks did a dumb, bad thing.  There is already too much being written about it, so instead I want to talk about this:



![Those are very accurate Superman-themed colors](/images/SuperbowlCaloriesMap.jpg)



This was [posted](http://dadaviz.com/i/3076) by [@dadaviz](https://twitter.com/dadaviz) and is pretty stark.  California, Texas, Florida, and New York are highest; The Rocky Mountain states are the lowest.  The astute among you may have already thought of [xkcd](https://xkcd.com)'s heatmap takedown:
[![There are also a lot of global versions of this map showing traffic to English-language websites which are indistinguishable from maps of the location of internet users who are native English speakers.](/images/heatmap.png)](https://xkcd.com/1138/)

The above Super Bowl map largely falls into that trap - California, Texas, Florida, and New York are, of course, the most heavily populated states, while Montana, Wyomong, and the Dakotas are pretty sparsely inhabited - rendering that map pretty uninformative.  Thankfully, the original publishers over at [BBDirect](http://www.bbdirect.com/blog/superbowl-food-fight) included another figure with the actual, per-state values:
![Per-state values, no superman](/images/SuperbowlCaloriesData.jpg).

This at least gives us something to work with.  Some quick R code later and...
![Tangled up in Blue](/images/updatedsbcals.png)

Ta-da!  Paints an entirely different picture, doesn't it?  The actual source of the data isn't very clear, so I'd like to avoid trying to interpret this[^1], but at the very least, people in the Northeast seem to be the heaviest eaters.  Maybe because it's so cold everyone just stays indoors and actually finishes the 7-layer dip?  Otherwise, the only real surprise is North Dakota.  They appear to be under-eating for their region.  I'm not sure why that would be, but would welcome any ideas!

-------------------------------------------------------------------------------
[^1]: The original posting by BBDirect makes it clear that this is either *old* data or *imputed* data, which is fine but of course places limits on further interpretation.


