---
layout: artwork
title: "Storyboard Escena 1"
image: "storyboard-1.jpg"
date: 2024-03-15
---

{% assign artwork_data = site.data.artwork | where: "image", page.image | first %}

{{ artwork_data.full_description | markdownify }}