---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
header:
  og_image: "images/profile.png"
---

Recording the dynamics of Horizontal Gene Transfer
======
Horizontal Gene Transfer (HGT) is a process that plays important roles in microbial ecology and evolution, as well as the spread of antibiotic resistance genes across environments. However, despite our ever-increasing understanding of the diversity and host ranges of mobile genetic elements, many knowledge gaps remain regarding the *dynamics* of how HGT occurs within environmental microbiomes. Filling such knowledge gaps would better inform strategies to mitigate the spread of antibiotic resistance gene and enable more informed risk assessments about the increasingly widespread usage of genetically engineered microbes in environmental settings.

My current work focuses on integrating novel synthetic biology tools and mathematical modeling to address these knowledge gaps and expand our fundamental understanding of HGT dynamics in the environment.

<p align='center'>
<img src='/images/HGT_dynamics_overview.png' width='600'>
</p>

Synthetic Biology in the Environment
======
One of the central challenges associated with translating synthetic biology advances in the laboratory into real-world applications is the fact that the environmental conditions that cells experience in a deployment context are different from those in the laboratory, often leading to unreliable system performance and outright system failure. This is particularly true when addressing sustainability applications, which will require the deployment of microbes into diverse environments such as agricultural soils, living materials, and water-treatment plants.

One of the goals of my research program is to uncover the principles by which environmental conditions impact the performance of genetic circuits, and to develop engineering strategies to ensure their reliable and predictable performance across environmental contexts.

<p align='center'>
<img src='/images/EnvPhysBehavior.png' width='600'>
</p>

My current projects on this theme fall under three main categories: experimental work studying the principles of microbial gene expression under different physiological states, theoretical work developing new ways to analyze biomolecular system behavior, and application-driven work developing methods to better understand and engineer the rhizosphere microbiome. More details on each of these areas can be found below.

<nbsp>

{% include base_path %}

{% assign ordered_pages = site.research | sort:"order_number" %}

{% for post in ordered_pages %} {% include archive-single.html type="grid" %} {% endfor %}
