---
layout: splash
title: "Clarity is more impressive than complexity."
permalink: /

header:
  overlay_color: "#05060a"
  overlay_filter: "0.8"

excerpt: "If your ideas take too long to explain, that’s usually the problem. When people tune out, something isn’t clear."

intro:
  - excerpt: "You can have a great idea and still lose people. All it takes is a few sloppy lines, a little jargon, and one paragraph that drags. People don’t stick around to decode it. They bounce."

feature_row_process:
  - title: "Most of my work starts before the writing does."
    excerpt: |
      I ask the questions that sort out what actually matters.  
      I organize the message before polishing the language.  
      I shape it into writing people can follow.
    image_path: /assets/images/jeff02.png

feature_row_fit:
  - title: "This tends to work well for people who:"
    excerpt: |
      - Are good at what they do, but find it hard to explain  
      - Want their audience to actually pay attention  
      - Care more about being understood than sounding impressive  

  - title: "It doesn’t work as well when:"
    excerpt: |
      - Jargon and buzzwords feel necessary  
      - Word count matters more than the message  
      - Sounding smart matters more than being understood  

feature_row:
  - title: "About Me"
    excerpt: "Quick overview of how I work and what you can expect."
    url: "/about/"
    btn_label: "About me"
    btn_class: "btn--primary"

  - title: "Blog"
    excerpt: "Clear, conversational writing about tech, systems, and real-world problem solving."
    url: "/blog/"
    btn_label: "Read posts"
    btn_class: "btn--primary"

  - title: "Hire Me"
    excerpt: "Need clear, human writing that explains complex ideas? Let’s talk."
    url: "/hire-me/"
    btn_label: "Work with me"
    btn_class: "btn--primary"
---

{% include feature_row id="intro" type="center" %}

{% include feature_row id="feature_row_process" type="left" %}

{% include feature_row id="feature_row_fit" %}

<section class="page__content" style="text-align:center; margin-top: 1.25rem;">
  <p style="font-size:1.05rem; margin-bottom: 0.75rem;">
    <strong>If this makes sense, start with About.</strong> Hire Me is the next step.
  </p>
</section>

{% include feature_row %}
