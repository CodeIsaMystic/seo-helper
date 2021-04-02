<div align="center">
<img src="assets/img/seo-main-img.jpg"/><br />

<h1>Search Engine Optimization Helper</h1><br />

<p>General overview of search engine optimization made from fork repo, links, researches and courses on that topic...</p>
</div>

## Table of content

- [Traditional SEO](course/TRADITIONAL.md)
  - [Physical Location](course/TRADITIONAL.md#physical-location)
  - [Page Rank](course/TRADITIONAL.md#pagerank)
  - [Long Tail Keywords](course/TRADITIONAL.md#long-tail-keywords)
  - [Keywords Planner Tools](course/TRADITIONAL.md#keywords-planner-tools)
  - [Link Building Campaign](course/TRADITIONAL.md#link-building-campaign)
  - [White hat VS Black hat](course/TRADITIONAL.md#white-hat-vs-black-hat)
  - [Bad Links](course/TRADITIONAL.md#bad-links)
  - [Ad Campaign](course/TRADITIONAL.md#ad-campaigns)
- [Meta Data](course/METADATA.md)
  - [The Basics](course/METADATA.md#basics-meta-tags)
  - [The OpenGraph](course/METADATA.md#opengraph-meta-tags)
    - [The Facebook OpenGraph](course/METADATA.md#facebook-opengraph)
    - [The Twitter Card](course/METADATA.md#twitter-card)
    - [The LinkedIN Inspector](course/METADATA.md#linkedin-inspector)
- [Structured Data](course/STRUCTUREDDATA.md)
  - [What Is This ?](course/STRUCTUREDDATA.md#what-is-this)
  - [What Does This Get Us ?](course/STRUCTUREDDATA.md#what-does-this-get-us)
  - [Breadcrumbs](course/STRUCTUREDDATA.md#breadcrumbs)
- [Mobile Optimization](course/MOBILEOPTIMIZATION.md)
  - [Intro](course/MOBILEOPTIMIZATION.md##Intro)
  - [Viewport](course/MOBILEOPTIMIZATION.md##The-viewport)
  - [Full Screen iOS](course/MOBILEOPTIMIZATION.md#The-Full-screen-Mode-(iOS))
  - [The Web App Manifest](course/MOBILEOPTIMIZATION.md#The-Manifest.json-(Android))
  - [Home Screen Icons](course/MOBILEOPTIMIZATION.md#Home-Screen-Icons)
  - [Add-to-home-screen](course/MOBILEOPTIMIZATION.md#Add-To-Home-Screen-Lib)
  - [Ultimate Test "Fit or Fat"](course/MOBILEOPTIMIZATION.md#The-Ultimate-test:-"Fit-Or-Fat"-app)
- [Accelerated Mobile Pages (AMP) Project](course/AMP.md)

## Problem

To help the SEO part of a developer job, we have to implement some method, find some solutions, sometimes some shortcuts or easy ways to complete tasks for what we are not specifically well experimented.
We find out some solutions from our google research routine, always trying to learn the bests practices.


## Solution

An helper repo on the topic with various tasks to do when building a project.

**NOTICE :** 
We removed on the following list the Ad Campaign, and the AMP Project sections on purposes. That is a basic helper on the SEO topic but not a professional and complete guide.

> This kind of "project" will be completed with time, it represent a starting point to have a better approach of Search Engine Optimization.

## SEO Practical

1. **The Physical Business Basic Job**
2. **The Page Rank Effort**
3. **The Long Tail Keywords Thought**
4. **The Link Build Campaign**
5. **The Bad links control**
6. **The Meta Data Work**  
7. **The Script Structured Data**
8. **The Mobile Optimization**

## Social Media meta tags templates

Social media meta tags allows you to add social information to your website or contents.
When you are sharing a url to social networks, they will find the social information which you defined between head tags.
In order to easily handle this routine on every project, we gather all the right meta tags on this repository.

- [standard-template](templates/standard-template.html)
- [minimal-template](templates/minimal-template.html)
- [full-template](templates/full-template.html)
- [templates folder](templates)

## Structured Data Breadcrumbs(script ld+json)

Make the search results more rich, and be sure that the infos are correct.
Some infos the crawlers are looking for, consistent and showed only on mobile devices.

A **Breadcrumbs script on ld+json format** usually inside the body tag. A json data structure with categories, types (sub-types) tp make some search cards results on mobile.

Get more control on the company/business infos and how they look (cards, images, icons...).

- [Schema.org website](https://schema.org/)
- [Structured Data Infos](course/STRUCTUREDDATA.md)
- [Breadcrumbs Model](breadcrumbs/breadcrumbs.html)

## Mobile Optimization

Google forked their search index in two categories.
We focus on **the way the app/website is fit** as on accessibility, performance or seo.

- [optimization.html](mobile-optimization/optimization.html)
- [manifest.json](mobile-optimization/manifest.json)
- [Optimization course](course/MOBILEOPTIMIZATION.md)


#### Links & Tools:
- [favicon set generator](https://realfavicongenerator.net/)
- [add-to-home-screen](https://github.com/cubiq/add-to-homescreen)
- [iOS simulator](https://appetize.io/)
- [lighthouse extension testing tool](https://chrome.google.com/webstore/detail/lighthouse/blipmdconlkpinefehnmjammfjpmpbjk?hl=fr) 

## Accelerated Mobile Pages (AMP)