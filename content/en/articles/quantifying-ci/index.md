---
title: "Quantifying CI"
description: ""
excerpt: ""
date: 2020-11-04T09:19:42+01:00
lastmod: 
draft: false
weight: 50
images: []
categories: ["articles"]
tags: ["standards"]
contributors: ["CITools"]
pinned: false
homepage: false
---

### Formalizing CI
Communication integrity is not boolean in nature.

Formally, we can define communication integrity as the weighted sum of variables 

* partisanship index

The virtually unlimited possibilities of expression through language is part of what make it such a powerful tool--the subtle evocation of thoughts, feelings, and layering of information, either by intent or accident, also make it nearly impossible to accurately quantify the true quality or purpose of a piece of writing. Modern tools for conducting sentiment analysis may be impressive, but also run the risk of reporting false results.

Nonetheless, once key parameters have been well defined, some communication neutrality and integrity metrics become easily quantifiable. Namely:

- partisan or partisan organization-affiliated author (Boolean)
- terminology used (Boolean)
- number of occurances of partisan terminology (integer)
- concentration of occurances of partisan terminology (decimal)
- partisan personalities or affiliated referenced or quoted (Boolean)
- number of partisan or affiliated personalities referenced or quoted (integer)
- concentration of quotes or references from partisan or affiliated personalities (decimal)
- partisan organization quoted or referenced (Boolean)
- number of partisan organizations quoted or referenced (integer)
- references to partisan publications (Boolean)
- number of references to partisan publications (integer)
- concentration of references to partisan sources (decimal)
- citation quality: minimum number of clicks to arrive on partisan content or source (integer)
- citation quality: average number of clicks to arrive on partisan content or source (decimal)

