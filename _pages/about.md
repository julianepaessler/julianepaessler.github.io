---
permalink: /
title: "Juliane Päßler"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a postdoctoral researcher in the [Automated Program Reasoning (APRe)](https://www.forsyte.tuwien.ac.at/groups/apre/) research group, which is part of the [forsyte](https://www.forsyte.tuwien.ac.at) research unit, at [TU Wien](https://www.tuwien.at).

My research interests include verification of self-adaptive systems and analysis of software product lines.

I obtained my PhD from the Faculty of Informatics at the University of Oslo in 2025 under the supervision of [Silvia Lizeth Tapia Tarifa](https://www.mn.uio.no/ifi/english/people/aca/sltarifa/index.html), [Einar Broch Johnsen](https://ebjohnsen.org), and [Carlos Hernández Corbato](https://chcorbato.github.io).
During my PhD, I was part of the Marie Skłodowska-Curie Actions Innovative Training Network [REMARO](https://remaro.eu) (REliable AI for MArine RObotics). 

I obtained my Bachelor's and Master's degree in mathematics from the University of Münster. 


## News

<div class="news-list">
{% assign sorted_news = site.news | sort: "date" | reverse %}
{% for item in sorted_news limit:5 %}
<div class="news-entry">
  <div class="news-date">{{ item.date | date: "%b %d, %Y" }}</div>
  <div class="news-content">{{ item.content }}</div>
</div>
{% endfor %}
</div>