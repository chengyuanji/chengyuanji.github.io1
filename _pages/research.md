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

1.Ji Chengyuan, Hanzhang Liu. “State as salesman: International economic engagement and foreign news coverage in China”, Political Communication, 2022, 39(1): 122-145. [[PDF](http://chengyuanji.com/files/Ji-and-Liu-2022-Political-Communication.pdf)][[Appendix](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=2956129)][[Replication](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/JNI6TO)]
