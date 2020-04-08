---
title: "Embed a PDF file viewer"
categories: blog
tags:
  - pdf
---

Embed PDF file powered by View.js

<div class="zoom-container" style="
    position: relative;
    padding-bottom:56.25%;
    padding-top:30px;
    height:0;
    overflow:hidden;
">
  <iframe
    src='{{ '/assets/js/viewer-js/' | relative_url }}#{{ '/assets/2019/pdf-sample-file.pdf' | relative_url }}'
    width='560'
    height='315'
    allowfullscreen
    webkitallowfullscreen
    frameborder="0"
    style="
      position: absolute;
      top:0;
      left:0;
      width:100%;
      height:100%;
    "
  ></iframe>
</div>
