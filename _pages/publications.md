---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

Journal Articles
===

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

Working Papers
===

{% for post in site.workingPapers reversed %}
  {% include archive-single.html %}
{% endfor %}

Policy Notes and Reports
===
{% for post in site.policyNotes reversed %}
  {% include archive-single.html %}
{% endfor %}
