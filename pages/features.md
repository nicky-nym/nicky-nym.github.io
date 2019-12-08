---
permalink: /features/
---
# Books

{% for book in site.data.features.books %}
  * **[{{ book.book }}]({{ book.link }})**, by {{ book.by }}
{% endfor %}

# Architectural features

{% for topic in site.data.features.topics %}
## {{ topic.topic }}
{% for term in topic.terms %}
  * <a name="{{ term.term }}"></a>**{{ term.term }}** -- {{ term.idea }}
{% for also in term.also %}     * __[{{ also }}](#{{ also }})__
{% endfor %}
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


