---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  For an updated list of publications see <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

Z. Gu, K.G. Smith, G.M. Alexander, I. Guerreiro, S.M. Dudek, B. Gutkin, P. Jensen, J.L. Yakel. *Hippocampal Interneuronal α7 nAChRs Modulate Theta Oscillations in Freely Moving Mice*, Cell Reports (2020)
[[journal]](https://www.cell.com/cell-reports/fulltext/S2211-1247(20)30720-8)

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
