---
layout: archive
title: "Project Descriptions"
permalink: /project_desc/
author_profile: false
---

{% include base_path %}

{% for post in site.project_desc reversed %}
  {% include archive-single.html %}
{% endfor %}