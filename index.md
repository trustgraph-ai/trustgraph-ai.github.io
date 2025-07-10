---
title: "This is a title"
metadata:
  information: An importan tpiece of information
layout: default
nav_order: 2
---

# {{ page.title }}

This is a test

Note: {{ page.metadata.information }}


```mermaid
graph TD;
    accTitle: the diamond pattern
    accDescr: a graph with four nodes: A points to B and C, while B and C both point to D
    A-->B;
    A-->C;
    B-->D;
    C-->D;
```

{: .warning }
A paragraph...


