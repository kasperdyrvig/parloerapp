---
layout: default
metaTitle: Grønlandsk parlør
onPageTitle: Grønlandsk Parlør
---

{% for gruppe in site.grupper %}
  <h2>{{gruppe.name}}</h2>
  {% assign ordgruppe = site.parloer | where: 'parentGroup', gruppe.group %}
  <ul>
  {% for group in ordgruppe %}
    <li>
        <a href="{{group.url | relative_url}}">{{ group.onPageTitle }}</a>
    </li>
  {% endfor %}
  </ul>
{% endfor %}
