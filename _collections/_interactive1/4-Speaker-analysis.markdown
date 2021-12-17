---
layout: post
title:  "Analysis of political speakers"
author: Tajat
date:   1776-02-14 20:20:35 +0200
image: ""
position: center
---
In the animation it can be seen how the number of quotes made by conservative and labour speakers for each newspaper changed over the years. A few general observations could be made: In 2015, a majority of the newspapers quoted more labour speakers but then a shift could be observed. In 2016 about half of the newspapers quoted more labour, and the other half more convervative. From 2017, a majority quoted more conservative speakers instead.  BBC and Independent followed this trend, quoting more labour in 2015 but more conservative thereafter. It could be noted that a few of the newspapers quoted more labour speakers after 2015 as well, especially Daily Record which did it all years. Also, Manchester Evening News, Liverpool Echo and Wales online quoted more labour speakers for most years. 

{% include animation_quotesperparty.html %}

 It was not easy to find any patterns when clustering the speaker frequency matrix using K-means. Trying something different, the speaker frequency matrix was projected onto a 2-dimensional space. Just to make the plot more interpretable, each newspaper was given a political stance according to the survey from 2017 made by YouGov, if applicable. Even when doing this, there is no clear pattern for any of the years. The newspapers move around over the map, having different neighbours each year.


{% include ploty_scatter.html %}

<!--more-->