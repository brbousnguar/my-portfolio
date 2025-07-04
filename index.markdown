---
layout: splash
permalink: /
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: /assets/images/splash-bg.jpg
  actions:
    - label: "View My Work"
      url: "/portfolio/"
  caption: "Welcome to my portfolio"
excerpt: "Software Developer passionate about creating amazing digital experiences"
intro: 
  - excerpt: 'Welcome to my portfolio website. Here you will find information about my projects, skills, and professional journey. Feel free to explore and get in touch!'

feature_row:
  - image_path: assets/images/unsplash-gallery-image-1-th.jpg
    alt: "placeholder image 1"
    title: "Projects"
    excerpt: "Check out some of my recent work and projects I've been involved in."
    url: "/portfolio/"
    btn_label: "View Projects"
    btn_class: "btn--primary"
  - image_path: /assets/images/unsplash-gallery-image-2-th.jpg
    alt: "placeholder image 2"
    title: "About Me"
    excerpt: "Learn more about my background, skills, and experience."
    url: "/about/"
    btn_label: "Learn More"
    btn_class: "btn--primary"
  - image_path: /assets/images/unsplash-gallery-image-3-th.jpg
    title: "Contact"
    excerpt: "Interested in working together? Let's get in touch!"
    url: "/contact/"
    btn_label: "Get in Touch"
    btn_class: "btn--primary"      
---

{% include feature_row id="intro" type="center" %}

{% include feature_row %}
