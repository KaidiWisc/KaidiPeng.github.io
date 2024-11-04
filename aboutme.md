---
layout: default
title : About Me
navbar_title: AboutMe
---

{% include widgets/debug_url.html %}

{% if site.data.display.homepage.show_experience %}
    {% include widgets/experience_card.html %}
{% endif %}
