---
layout: archive
author_profile: true
---

{% include base_path %}

{% for post in site.theory %}
  {% include archive-single.html %}
{% endfor %}
{% for post in site.apply %}
  {% include archive-single.html %}
{% endfor %}
{% for post in site.sci-tech %}
  {% include archive-single.html %}
{% endfor %}
{% for post in site.others %}
  {% include archive-single.html %}
{% endfor %}
