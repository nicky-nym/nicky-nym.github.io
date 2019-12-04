<ul>
{% for member in site.data.features %}
  <li>
      {{ features.name }}
  </li>
  <li>
      {{ features.definition }}
  </li>
{% endfor %}
</ul>
