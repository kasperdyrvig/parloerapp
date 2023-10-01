---
layout: default
name: Basale ord
metaTitle: Basale ord
onPageTitle: Basale ord
group: basic
is-phrasegroup: true
---

{% assign ordgruppe = site.pages | where: 'phrasegroup', page.group %}
<ul>
{% for group in ordgruppe %}
<li>
    <a href="{{group.url | relative_url}}">{{ group.onPageTitle }}</a>
</li>
{% endfor %}
</ul>