---
layout: archive
# title: "Research"
permalink: /research/
author_profile: true
---

You can find (an almost complete list of) my articles on <u><a href="{{ site.author.googlescholar }}" target="_blank">my Google Scholar profile</a></u> and <u><a href="{{ site.author.researchgate }}" target="_blank">my ResearchGate profile</a></u>.

# Selected Publications

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
