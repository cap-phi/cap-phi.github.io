---
layout: category
permalink: /wikipedia/
---

{% for thing in site.wikipedia %}
  <h2> 
    <a href="{{ thing.url }}">
      {{ thing.title}}
    </a>
  </h2>
{% endfor %}

<!-- {% for staff_member in site.staff_members %}
  <h2>
    <a href="{{ staff_member.url }}">
      {{ staff_member.name }} - {{ staff_member.position }}
    </a>
  </h2>
  <p>{{ staff_member.content | markdownify }}</p>
{% endfor %} -->