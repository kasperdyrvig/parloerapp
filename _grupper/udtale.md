---
layout: default
name: Hjælp til udtale
metaTitle: Hjælp til udtale
onPageTitle: Hjælp til udtale
group: pronunciation
---

{% assign ordgruppe = site.parloer | where: 'parentGroup', page.group %}
<ul>
{% for group in ordgruppe %}
<li>
    <a href="{{group.url | relative_url}}">{{ group.onPageTitle }}</a>
</li>
{% endfor %}
</ul>