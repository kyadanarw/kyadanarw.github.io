---
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar]((https://scholar.google.co.th/citations?hl=en&user=3Bi3itoAAAAJ&view_op=list_works&sortby=pubdate}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
You can also find my articles on [Google Scholar](https://scholar.google.co.th/citations?hl=en&user=3Bi3itoAAAAJ&vi ew_op=list_works&sortby=pubdate)

# Peer-Reviewed Journals
[Ensemble Deep Learning for the Detection of COVID-19 in Unbalanced Chest X-ray Dataset](https://doi.org/10.3390/app112210528) 
*Khin Yadanar Win, Noppadol Maneerat, Kazuhiko Hamamoto and Syna Sreng,Applied Sciences, 2021, 11(22), p.10528.<br/>
Download [here](https://doi.org/10.3390/app112210528)
