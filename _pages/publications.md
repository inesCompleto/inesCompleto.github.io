---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  For an updated list of publications see <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

**I.C. Guerreiro**, C. Clopath. *Memory’s gatekeeper: The role of PFC in the encoding of congruent events*, PNAS (2024)
[[pdf]]()

**I. Guerreiro**, Z. Gu, J.L. Yakel, B.S. Gutkin. *Recurring Cholinergic Inputs Induce Local Hippocampal Plasticity through Feedforward Disinhibition*, eNeuro (2022)
[[pdf]](http://inesCompleto.github.io/files/Guerreiro_2022.pdf)
[[journal]](https://www.eneuro.org/content/9/5/ENEURO.0389-21.2022.abstract)
[[bioRxiv]](https://www.biorxiv.org/content/10.1101/2020.10.13.337188v2.abstract)
[[github]](https://github.com/inesCompleto/Hippocampal_Plasticity)

Z. Gu, K.G. Smith, G.M. Alexander, **I. Guerreiro**, S.M. Dudek, B. Gutkin, P. Jensen, J.L. Yakel. *Hippocampal Interneuronal α7 nAChRs Modulate Theta Oscillations in Freely Moving Mice*, Cell Reports (2020)
[[pdf]](http://inesCompleto.github.io/files/Gu_2020.pdf)
[[journal]](https://www.cell.com/cell-reports/fulltext/S2211-1247(20)30720-8)

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
