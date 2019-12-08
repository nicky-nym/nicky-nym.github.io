---
permalink: /features/
---
# Books

{% for book in site.data.features.books %}
  * **[{{ book.book }}]({{ book.link }})**, by {{ book.by }}
{% endfor %}

# Architectural features

{% for term in site.data.features.terms %}
  * <a name="{{ term.term }}"></a>**{{ term.term }}**
{{ if term.idea }}    * {{ term.idea }}{% endif %}
{% for also in term.also %}     * __[{{ also }}](#{{ also }})__
{% endfor %}
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


