---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

Climate change is the defining issue facing our generation and generations to come. Its underlying driver is clear - accumulated greenhouse gases, emitted from fossil fuel exploitation, absorb infrared radiation and cause global warming. However, a large but highly uncertain fraction of the warming has been *masked* by atmospheric aerosol particles, via their direct effect of reflecting incoming solar radiation and indirect effect of serving as seeds for cloud formation. The poorly-understood interactions between particles and clouds lead to the major uncertainty in total anthropogenic radiative forcing that directly translates to a wide range in the projected warming: 2.5-4 &deg;C for a doubling of CO~2~ expected by about 2050.

We


<nbsp>

{% include base_path %}

{% assign ordered_pages = site.research | sort:"order_number" %}

{% for post in ordered_pages %}
  {% include archive-single.html type="grid" %}
{% endfor %}
