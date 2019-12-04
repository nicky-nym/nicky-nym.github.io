---
permalink: /features/
---
# Architectural features


<ul>
{% for term in site.data.features.terms %}
  <li>
      {{ term.term }}
  </li>
  <li>
      {{ term.definition }}
  </li>
{% endfor %}
</ul>

{% for term in site.data.features.terms %}
  * {{ term.term }}: {{ term.definition }}
{% endfor %}

  
