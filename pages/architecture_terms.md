---
permalink: /architecture/
---

# Architectural features & terminology

## Books & dictionaries

{% for book in site.data.features.books %}
  * **[{{ book.book }}]({{ book.link }})**, by {{ book.by }}
{% endfor %}

## Glossary

{% for topic in site.data.features.topics %}
## {{ topic.topic }}
{% for term in topic.terms %}
  * <a name="{{ term.term }}"></a>**{{ term.term }}** -- {{ term.idea }}
{% for also in term.also %}     * __[{{ also }}](#{{ also }})__
{% endfor %}
{% capture num_pics %} {{ term.pics | size | minus:1 }} {% endcapture %}
{% unless num_pics contains '-' %} <details style='margin-left: 60px'>
<summary>examples</summary>
{% for pic in term.pics %}
<img src="{{ pic }}">
{% endfor %}
</details>
&nbsp;
{% endunless %}
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


