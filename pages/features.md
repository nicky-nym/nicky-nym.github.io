---
permalink: /features/
---
# Architectural features


<ul>
{% for feature in site.data.features %}
  <li>
      {{ feature.name }}
  </li>
  <li>
      {{ feature.definition }}
  </li>
{% endfor %}
</ul>
