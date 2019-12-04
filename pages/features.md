---
permalink: /features/
---
# Architectural features

{% for term in site.data.features.terms %}
  * **{{ term.term }}**
    * {{ term.idea }}
    * {% for also in term.also %} __{{ also }}__, {% endfor %}
{% endfor %}
  
<!--
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
-->

<!--
{% for term in site.data.features.terms %}
  * {{ term.term }}: {{ term.definition }}
{% endfor %}
-->


