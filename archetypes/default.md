---
title: '{{ replace .File.ContentBaseName "-" " " | title }}'
date: {{ .Date }}
tags: ["news"]
categories: ["news"]
author: "Me"
draft: true
description: "Description Text"
canonicalURL: "https://canonical.url/to/page"
cover:
    image: "<image path/url>" # image path/url
    alt: "alt text" # alt text
    caption: "display caption under cover" # display caption under cover
---