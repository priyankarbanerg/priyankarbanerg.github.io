---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---
<p>I am interested in studying the dynamics of quantum systems at low temperatures. So far, I have investigated many-body systems coupled via photon-phonon or photon-atom interaction to study quantum metrology.<br>
For my Master's thesis, I worked on a scheme to induce robust squeezing in the mechanical mode below the standard quantum limit. I have also done a project on the time evolution of squeezing in the two-photon Dicke model (TPDM). <br>
Other smaller projects I've done or currently doing have been underlined in my CV. With my experience and desire to couple simulation with the analytical study, I would like to employ condensed matter theoretical approach to solve problems in quantum optics and quantum information.</p> 
{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
