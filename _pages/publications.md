---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  2020\. "Implicit and explicit state attachment among single and dual American citizens." _Politics, Groups, and Identities_ (with Aleksander Ksiazkiewicz) <u><a href="{{https://doi.org/10.1080/21565503.2020.1789884}}">Link</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
