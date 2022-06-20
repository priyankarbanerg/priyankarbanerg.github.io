---
layout: archive
title: "Research Overview"
permalink: /research/
author_profile: true
---
<p>I am interested in studying the dynamics of quantum systems at low temperatures. So far, I have investigated many-body systems coupled via photon-phonon or photon-atom interaction to study quantum metrology.<br>
For my Master's thesis, I worked on a scheme to induce robust squeezing in the mechanical mode of cavity optomechanical system below the standard quantum limit. We achieved this by modulating the amplitude of the driving field. I have also done a project where I studied the time evolution of squeezing in the two-photon Dicke model (TPDM). We showed that the squeezing time is prolonged in a region away from the critical phase boundary of the TPDM.<br>
Other smaller projects I've done or currently doing have been underlined in my CV. With my experience and desire to couple simulation with the analytical study, I would like to employ condensed matter theoretical approach to solve problems in quantum optics and quantum information.</p>

<h2>Publications</h2>

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
