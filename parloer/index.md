---
layout: default
metaTitle: Grønlandsk parlør
onPageTitle: Grønlandsk Parlør
---

{% assign phrasegroups = site.pages | where: 'is-phrasegroup', true %}
{% for phrasegroup in phrasegroups %}
  <h2>{{phrasegroup.onPageTitle}}</h2>
  {% assign phrases = site.pages | where: 'phrasegroup', phrasegroup.group %}
  <ul>
  {% for phrase in phrases %}
    <li>
        <a href="{{phrase.url | relative_url}}">{{ phrase.onPageTitle }}</a>
    </li>
  {% endfor %}
  </ul>
{% endfor %}
