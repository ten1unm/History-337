---
title: "HIS 337 US since 1945"
layout: base
date: 2025-10-21
header-image: "/assets/images/twentieth-century-mural-1.jpg"
header-title: US Culture & Society since 1945 
header-subtitle: a class project template
header-position: 35% center
---

# US Culture & Society since 1945 

This is the HIS 337 class website for the student final projects using [Xanthan framework](https://xanthan-web.github.io/xanthan/). Everything you see here is a placeholder — the title above, the essay topics, the images. 

This opening section will introduce your topic and lay our your argument about why the topic you have chosen and researched is significant and/or relevant for understanding U.S. history between 1945-2000s. Remember that all of your webpage content will need to support and develop this argument in some way. Because a webpage communicates information in sections or more digestible portions, you will want to consider how each section or portion below develops a particular point of your argument. [^source1]  

 To get a sense of what a finished project can look like, this template includes three sample essays on Southwest food history, generated with AI as stand-ins for real student work. Because a webpage communicates information in sections or more digestible portions, you will want to consider how each section or portion contributes to your overall argument. Browse them to see how essays can use images, pull quotes, and scroll-driven backgrounds. Then start replacing them with your own material. Note that images, pull quotes, and videos are all ways to break up the sections for reader engagement. 

**Ready to begin?** Open `index.md` in your editor and change the title and this introduction. That's your first edit. The [documentation](docs/) covers everything else — how to add pages, configure navigation, set up student contributors, and customize the look.

The card grid below links to the sample essays. The info on these cards come from the essay pages themselves. As students publish their essaysm, these will showcase students' work as the project develops.

{% assign all_pages = site.pages %}
{% assign cards = all_pages | where_exp: "p", "p.path contains 'essays/'" | where_exp: "p", "p.path != 'essays/index.md'" %}

{% include nav/card-grid.html cards=cards %}

[^source1]: We will only use footnote references (CMOS 18th ed) for the webpage for visual simplicity.
