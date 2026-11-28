---
title: "Home"
layout: homelay
permalink: /
---

<h1 class="home-hero">Sanli Research Group</h1>
<p class="home-hero-sub">{{ site.title }}, {{ site.institution }}</p>

<div class="chip-container" markdown="0">
<a href="{{ '/research' | relative_url }}" class="chip">Functional Polymers </a>
<a href="{{ '/research' | relative_url }}" class="chip">Flexible Bioelectronics</a>
<a href="{{ '/research' | relative_url }}" class="chip">Sensors and Actuators</a>
<a href="{{ '/research' | relative_url }}" class="chip">Nanotechnology</a>
</div>

Theoretical physics is a branch of physics that focuses on the development of mathematical models and theories to understand and explain natural phenomena.
It plays a crucial role in our understanding of the fundamental laws of the universe and the fundamental particles that make up all matter.
Research in theoretical physics helps us to make predictions about how the universe works and to test these predictions through experiments.

<div class="callout callout-success" markdown="0">
<div class="callout-title">{% include icon.html name="award" class="callout-icon" %} Nobel Prize in Physics, 1965</div>
<p>Awarded the Nobel Prize jointly with Julian Schwinger and Shin'ichiro Tomonaga for fundamental work in quantum electrodynamics, with deep-ploughing consequences for the physics of elementary particles.</p>
</div>

<div class="banner-frame" markdown="0">
<img src="{{ '/images/banner.webp' | relative_url }}" alt="Feynman diagrams" width="1400" height="449" loading="lazy">
<div class="banner-caption">Examples of Feynman diagrams. Feynman R., <em>The theory of positrons. Phys. Rev.</em> (1949)</div>
</div>

{% capture selected %}{% bibliography --query @*[selected=true] %}{% endcapture %}
{% if selected contains "pub-entry" %}
## Selected publications

<div class="section-card selected-pubs" markdown="0">
{{ selected }}
<p style="margin: var(--space-4) 0 0;"><a href="{{ '/publications' | relative_url }}">All publications &rarr;</a></p>
</div>
{% endif %}

## About me

Experienced researcher specializing in bioelectronics, functional polymers, and nanocomposites, with expertise in designing sustainable, high-performance materials for multifunctional sensing, autonomous drug delivery, and digital diagnostics. Integrates nanotechnology and polymer science to develop biodegradable, recyclable, and multifunctional materials for advanced biomedical and healthcare applications.
