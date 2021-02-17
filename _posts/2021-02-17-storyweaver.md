---
layout: post
title: StoryWeaver
date: 2021-02-17 13:32:20 +0300
description: You’ll find this post in your `_posts` directory. Go ahead and edit it and re-build the site to see your changes. # Add post description (optional)
img: storyweaver.png # Add image post (optional)
fig-caption: # Add figcaption (optional)
tags: [Education, Children]
projects: 2
technologies: Ruby on Rails, React, Postgres, ElasticSearch
---

StoryWeaver is an open source platform by Pratham Books for multilingual children’s stories.
It addresses all the issues around the lack of content by using an open access framework and
technology as force multipliers combined with a platform that supports translation and 
re-mixing av stories.

* **Website**: [https://storyweaver.org.in/](https://storyweaver.org.in/)
* **Digital Public Good**: Reviewed by the [Early Grade Reading Community of Practice](https://digitalpublicgoods.net/blog/announcing-the-first-vetted-digital-public-goods-for-foundational-literacy-and-early-grade-reading/) in July 2020.
* **Repositories**:
	* https://github.com/PrathamBooks/sw-core
	* https://github.com/PrathamBooks/sw-web

<p>&nbsp;</p>

## Project 1: SDK for StoryWeaver reader experience 
StoryWeaver progressive web app (PWA) has a content reader experience built which allows
easy consumption of stories (both online/offline) on the platform for children who are in
the stage of developing the conceptual model of associating words with their corresponding
visual representation. This project would aim to build a Software Development Kit (SDK)
which could allow porting this reader experience to mobile platforms (Android/iOS).

**Expected Impact**: The easy to use web reader experience availability via SDK would encourage
developers on mobile platforms to recreate the seamless reading experience on mobile.

**Deliverable**: SDK for reader experience with a dummy Android app using the SDK for the
currently available PWA reader experience

<p>&nbsp;</p>

## Project 2: Predictive Multilingual search on StoryWeaver

StoryWeaver supports story consumption in ~280 languages including a lot of underserved
languages.  The aim of this project is to build a predictive search platform which supports
this large language scalability.

**Expected Impact**: A predictive search available in native underserved languages would
help users easily discover high quality content available on the platform.

**Deliverable**: A multilingual predictive search module using open-source tools like
ElasticSearch which can be integrated on the current StoryWeaver platform.
