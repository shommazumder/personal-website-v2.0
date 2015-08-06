---
layout: article
title: "Homelessness as a Data Problem"
author: shom_mazumder
categories: articles
excerpt: "Using machine learning methods to combat homelessness."
tags: [machine learning, homelessness, civic hacking, social good]
comments: true
image:
  teaser: homelessness-infographic.jpg
---

{% include toc.html %}

##The Problem

For the last 4 years, I lived in [Washington, DC](http://www.buzzfeed.com/bennyjohnson/the-7-most-heinously-ugly-government-buildings-in-washington#.pnEV8qQYvV) as an undergraduate student at [Georgetown University](https://www.georgetown.edu/). Well more specifically, I lived in the neighborhood of Georgetown--an incredibly affluent neighborhood in Northwest DC. 

One of the things that I noticed while living there was the stark disparity in socioeconomic conditions. DC--like many other major cities--is a tale of two cities. The rich folk live in one DC while the poorer folk live in another. 

![Geographic Distribution of Poverty in DC]({{site.url}}/images/dcmapincome.jpg)

Homelessness, one of the cruelest forms of poverty, is a fact of life for a [large number](http://apps.washingtonpost.com/g/page/local/homelessness-in-metropolitan-washington/1033/) of people living in DC. A confluence of economic, social, and cultural forces lead residents to lose their homes, and these have real impacts on both the lives of the poor and society by reducing lifetime earnings, generating strains on public services, increasing the risk of drug-abuse, etc. etc. It's also likely that increased time on the streets exacerbates these detrimental effects.

Given these personal and social costs and the very limited resources that many local governments and non-profits have to combat homelessness, finding an efficient way to direct resources to reduce the likelihood that an individual/family becomes homeless in the first-place should be a first-order objective. So the data problem, then, is how can we figure out the risk factors for homelessness and target our resources to communities where individuals face an elevated risk of homelessness? 

##A Solution?
This seems to me like an ideal ground to deploy machine learning tools to predict an individual/family's homelessness risk. Since we have reasonably good data on things like economic conditions, housing prices, housing evictions, and crime statistics, which are intuitively associated with increased homelessness risk, implementing an early-warning system for major cities shouldn't be too hard once you gather and process the data. Training a model on this data and giving local governments and social workers an easy way to work with the results seems like something that would greatly benefit this space.

One of the things that makes this particularly exciting for me is that such an approach is ripe for collaboration across various communities. Civil servants, social workers, and those who have experienced homelessness have the deep substantive knowledge to inform what risk factors a model should look at. Data scientists and software engineers have the technical know-how to implement a machine-learning solution. Put these two groups into one space and I think we'll be quite pleased with the results. 

Obviously there are privacy issues at stake with such a project, but I think the potential benefits of such a targeting system likely outweigh the costs. There are ways to alleviate privacy concerns such as targeting flyers or mail that highlight housing resources to communities rather than individuals that still would achieve . 

By creating a system that allows social workers to target their efforts, we can free up more resources to run randomized evaluations that judge the impact of various interventions. Once we figure out some of the factors that systematically predict homelessness risk, we can move toward developing and fine-tuning interventions that fit the individual needs for each community. 

A data-driven approach to combating homelessness, of course, is no be-all-end-all, but it seems like a low-cost, high-impact approach to tackling this tough problem. So that begs the question, if this is so easy, then why hasn't it been done yet? An organization called [SumAll.org](http://www.sumall.org/project-overview/homelessness) does something that looks pretty similar to what I outlined above, but it looks like it has really only been rolled out to NYC. Nevertheless, it looks like a pretty good start to tackling some of the core data issues inherent to homelessness prevention. I should also mention that my former employer, [Palantir Technologies](https://www.palantir.com/philanthropy-engineering/annual-report/2014/#homelink), also tackles a similar data problem in its work on Homelink--a system that helps caseworkers connect veterans to housing. Both of these projects seem like they deliver results, so why not iterate and expand on their efforts?

Have ideas, comments, or experience in this area? Feel free to comment below to start a discussion about how we can make this happen!