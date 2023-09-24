---
layout: default
metaTitle: Regler for grønlandsk udtale | Grønlandsk parlør
onPageTitle: Udtaleregler
parentGroup: pronunciation
---

<ul>
{% for word in site.data.pronunciation.rules.words %}
  <li>
      {{ word.greenlandic }}
  </li>
{% endfor %}
</ul>