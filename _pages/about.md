---
permalink: /
layout: splash
author_profile: false
redirect_from: 
  - /about/
  - /about.html
title: "Standard Operating Procedure (SOP)"
excerpt: "hello"
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: high_qual_soup.png
  actions:
    - label: "Download"
      url: "https://github.com/mmistakes/minimal-mistakes/"
  caption: "Photo credit: **Jon!**"
excerpt: "SOPs are modular materials that, if followed, help guide the production of standardized, replicable research."
intro: 
  - excerpt: 'Below are a few highlighted SOPs we have available!'
feature_row:
  - image_path: high_qual_soup.png
    alt: "placeholder image 1"
    title: "Homology & De Novo Modeling"
    excerpt: "The image itself can be a **link.**"
  - image_path: high_qual_soup.png
    image_caption: "Image courtesy of [Unsplash](https://unsplash.com/)"
    alt: "placeholder image 2"
    title: "Small Molecule Docking, Validation"
    excerpt: "Look, we can have a **button** (currently not functional)."
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
  - image_path: high_qual_soup.png
    title: "Molecular Dynamics Simulations"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."
feature_row2:
  - image_path: high_qual_soup.png
    alt: "placeholder image 2"
    title: "Placeholder Image Left Aligned"
    excerpt: 'This is some sample content that goes here with **Markdown** formatting. Left aligned with `type="left"`'
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
feature_row3:
  - image_path: high_qual_soup.png
    alt: "placeholder image 2"
    title: "Placeholder Image Right Aligned"
    excerpt: 'This is some sample content that goes here with **Markdown** formatting. Right aligned with `type="right"`'
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
feature_row4:
  - image_path: high_qual_soup.png
    alt: "placeholder image 2"
    title: "Placeholder Image Center Aligned"
    excerpt: 'This is some sample content that goes here with **Markdown** formatting. Centered with `type="center"`'
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
---

{% include feature_row id="intro" type="center" %}

{% include feature_row %}

{% include feature_row id="feature_row2" type="left" %}

{% include feature_row id="feature_row3" type="right" %}

{% include feature_row id="feature_row4" type="center" %}