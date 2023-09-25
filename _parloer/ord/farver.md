---
layout: default
metaTitle: Farver
onPageTitle: Farver
parentGroup: basic
currentGroup: color
---

<div>
{% assign entries = site.dictionary | where: 'category', page.currentGroup %}
{% for entry in entries %}
  {% include parloerentry.html kl=entry.greenlandic da=entry.danish %}
{% endfor %}
</div>