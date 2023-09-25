---
layout: default
metaTitle: Regler for grønlandsk udtale | Grønlandsk parlør
onPageTitle: Udtaleregler
parentGroup: pronunciation
---

<div>
{% for entry in site.data.pronunciation.rules.words %}
  {% include parloerentry.html kl=entry.greenlandic da=entry.danish %}
{% endfor %}
</div>