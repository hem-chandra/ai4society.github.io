---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% include base_path %}
{% for post in site.projects reversed %}
   	{% include archive-publication.html %}  
{% endfor %}




