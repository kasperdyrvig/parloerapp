---
layout: default
metaTitle: Farver
onPageTitle: Farver
phrasegroup: basic
subgroup: color
---

<div>
{% assign entries = site.phrases | where: 'phrasesubgroup', page.subgroup %}
{% for entry in entries %}
  {% include parloerentry.html kl=entry.greenlandic da=entry.danish %}
{% endfor %}
</div>