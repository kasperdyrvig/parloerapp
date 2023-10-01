---
layout: default
metaTitle: Regler for grønlandsk udtale | Grønlandsk parlør
onPageTitle: Udtaleregler
phrasegroup: pronunciation
subgroup: rules
---

<div>
{% assign entries = site.phrases | where: 'category', page.subgroup %}
{% for entry in entries %}
  {% include parloerentry.html kl=entry.greenlandic da=entry.danish %}
{% endfor %}
</div>