---
layout: default
metaTitle: Farver
onPageTitle: Farver
parentGroup: basic
---

<ul>
{% for word in site.data.basic.colors.words %}
  <li>
      {{ word.greenlandic }}
  </li>
{% endfor %}
</ul>