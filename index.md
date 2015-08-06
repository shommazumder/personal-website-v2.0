---
layout: archive
permalink: /
title: "Politics+Data+Coffee=Shom"
excerpt: "Political science to save the world."
image:
 feature: world-light.jpg
---
{: .squish .center}

This is the personal website of Shom Mazumder. I am currently a PhD student in the [Department of Government at Harvard University](http://www.gov.harvard.edu/). Substantively, I study international and comparative political economy. My research branches off into two overarching themes. First, under what conditions do international and domestic actors learn from each other under repeated interaction? Second, what are the historical roots of contemporary political and economic phenomena? 

To get at these questions, I use a diverse set of methodological tools including but not limited to econometeric, machine learning, archival, and social network analysis. I'm also interested in thinking about new ways in which scholars can leverage diffusion-type behavior to approximate quasi-experimental designs in the analysis of observational data, applying Bayesian inference to substantive questions in international relations, and creating scalable ways for social scientists to interact with data. 

On the side, I'm interested in evaluating different methods and recipes to brew coffee. 
{: .squish .center}

## [Research]({{ site.url }}/research/)
{: .squish .center}

<div class="tiles">
{% for post in site.categories.research limit:3 %}
  {% include archive-tiles.html %}
{% endfor %}
</div><!-- /.tiles -->

## [Blog Articles]({{ site.url }}/articles/)
{: .squish .center}

<div class="tiles">
{% for post in site.categories.articles limit:3 %}
  {% include archive-tiles.html %}
{% endfor %}
</div><!-- /.tiles -->
