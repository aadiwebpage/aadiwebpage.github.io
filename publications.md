---
layout: publications
title: Publications
permalink: /publications/
years: [
2024,
2023,
2022,
2021,
2020,
2019,
2018,
2017,
2016,
2015,
2014,
2013,
2012,
2011,
2010,
2009,
2008,
2007,
2006,
2005,
2004,
2003,
2002,
2001,
2000,
1999,
1998,
1996,
1995,
1994
]

---

{% for y in page.years %}
  <h3 class="home-title">{{y}}</h3>
  {% bibliography -f tumer -q @*[year={{y}}]* --sort_by %}
{% endfor %}
