---
layout: single
author_profile: true
---

# Welcome to My Portfolio

I'm a passionate software developer with experience in web development, programming, and creating digital solutions. Welcome to my portfolio website where you can learn more about my work and connect with me.

## What I Do

- **Web Development**: Creating responsive and user-friendly websites
- **Software Engineering**: Building robust applications and systems
- **Problem Solving**: Tackling complex technical challenges
- **Continuous Learning**: Staying current with new technologies and best practices

## Recent Posts

{% for post in site.posts limit:3 %}
- [{{ post.title }}]({{ post.url }}) - {{ post.date | date: "%B %d, %Y" }}
{% endfor %}

## Get In Touch

Feel free to explore my work and don't hesitate to reach out if you'd like to connect or collaborate on a project!
