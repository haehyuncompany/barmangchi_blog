---
title: " "
layout: splash
permalink: /splash-page/
date: 2020-04-08
header:
  overlay_color: "#FFAB00"
  #overlay_filter: "0.5"
  # overlay_image: /assets/splash/laptop.jpeg
# excerpt: Hi! I'm Jan Meppe. Welcome to my little corner of the internet! I built this site to write and document everything that I've learned in data science and programming. Enjoy!
intro: 
  - excerpt: '발망치 홈페이지에 오신 여러분을 환영합니다.'
feature_row:
  - image_path: /assets/icon.png
    title: "Placeholder 1"
    excerpt: "Sample text 1 with **markdown** formatting."
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
  - image_path: /assets/icon.png
    title: "Placeholder 2"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--secondary"
  - image_path: /assets/icon.png
    title: "Placeholder 3"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--success"
feature_row_left:
  - image_path: /assets/icon.png
    title: "Left aligned placeholder 1"
    excerpt: "Left-aligned image centered with"
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
feature_row_right:
  - image_path: /assets/icon.png
    title: "Placeholder 1"
    excerpt: "Right-aligned image with ``"
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
feature_row_center:
  - image_path: /assets/icon.png
    title: "Placeholder 1"
    excerpt: "Center aligned image"
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
---

{% include feature_row id="intro" type="center" %}

{% include feature_row %}

{% include feature_row id="feature_row_left" type="left" %}

{% include feature_row id="feature_row_center" type="right" %}

{% include feature_row id="feature_row_center" type="center" %}
