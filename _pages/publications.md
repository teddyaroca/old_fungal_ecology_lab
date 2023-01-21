---
title: "The Fungal Ecology Lab - Publications"
layout: gridlay
excerpt: "The Fungal Ecology Lab -- Publications."
sitemap: false
permalink: /publications/
---


# Publications

---

## Featured

{% assign number_printed = 0 %}
{% for publi in site.data.publist %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if publi.highlight == 1 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-6 clearfix">
 <div class="row">
 	<img src="{{ site.url }}{{ site.baseurl }}/images/pubpic/{{ publi.image }}" class="img-responsive" width="25%" style="float: right" />
  <p><a class="pub1" href="{{ publi.link.url }}">{{ publi.title }}</a></p>
  <a class="pub2"> {{ publi.link.display }} </a>
 </div>
</div>

{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd == 1 %}
</div>
{% endif %}

{% endif %}
{% endfor %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if even_odd == 1 %}
</div>
{% endif %}

<p> &nbsp; </p>

---

<div>
## Full List

For a full list, please go to <a class="regtext" href="https://scholar.google.com/citations?user=JbabatgAAAAJ&hl=en">Google Scholar</a> or <a class="regtext" href="https://orcid.org/0000-0002-7567-4363">ORCID</a>.
<br><br><br>

</div>

