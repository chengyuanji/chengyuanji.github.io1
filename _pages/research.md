---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

1.Ji Chengyuan, Hanzhang Liu. “State as salesman: International economic engagement and foreign news coverage in China”, Political Communication, 2022, 39(1): 122-145. [PDF][Appendix][Replication]
