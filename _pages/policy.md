---
layout: archive
title: "Public Policy"
permalink: /policy/
author_profile: true
header:
  og_image: "images/profile.png"
---

The first genetically engineered organism intended for application in the open environment was a bacterium, *Pseudomonas putida*, developed by Ananda Chakrabarty at General Electric in 1971 to degrade crude oil. However, despite their historical primacy, a combination of regulatory uncertainty and public skepticism (exemplified by the case of the [Frostban field trials](https://en.wikipedia.org/wiki/Ice-minus_bacteria)) meant that engineered microbes intended for environmental release (EMERs) were never widely commercialized in the 20th century, and our frameworks for regulating, governing, and conceptualizing the interaction between engineered organisms and the environment were primarily developed around plants in agricultural contexts.

With the emergence of synthetic biology in the 21st century, however, we are now seeing a rapid re-emergence of EMERs in the commercial sector. Microbes exhibit many biological properties that make them distinct from plants in matters related to risk analysis and regulation, such as their microscopic size, asexual reproduction, and propensity for horizontal gene transfer. How should governance and regulatory bodies around the world respond to this rapidly accelerating industry? A major part of my work is to convene discussions across different disciplines and stakeholders to address these questions. Some more details about specific activities can be found below.

<nbsp>

{% include base_path %}

{% assign ordered_pages = site.policy | sort:"order_number" %}

{% for post in ordered_pages %} {% include archive-single.html type="grid" %} {% endfor %}