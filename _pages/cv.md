---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Current academic positions
======
* 2024 - present: Postdoctoral Research Fellow
  * Bocconi University, Bocconi Institute for Data Science and Analytics ([BIDSA](https://www.bidsa.unibocconi.eu/wps/wcm/connect/Site/Bidsa/Home))
  * Supervisor: Prof. [Daniele Durante](https://danieledurante.github.io/web/)
  * Project: Causes of deAth dependence stRuctures and the cOmpositioNal effecT on ovErall mortality ([CARONTE](https://danieledurante.github.io/web/caronte.html))

Past academic positions
======
* 2023 - 2024: Postdoctoral Research Fellow, 
  * University of Padova, Department of Statistical Sciences
  * Supervisor: Prof. [Davide Risso](https://drisso.github.io/index.html)
  * Project: Statistical methods and models for the integration of multiomic data

Education
======
* 2019 - 2023: Ph.D. in Statistical Sciences, University of Padua
* 2016 - 2018: M.S. in Statistical Sciences, University of Padua
* 2013 - 2016: B.S. in Statistics for Economics and Finance, University of Padua, 2016

Work experience
======
* January 2019 - September 2019: Junior consultant in business intelligence and analytics
  * Company: Blue BI S.R.L.
  
Skills
======
* Advanced knowledge of R, C++, Python and Julia
* Good knowledge of Stan and Keras
* Basic knowledge of Matlab
* Good knowledge of LaTeX
* Basic knowledge of MySQL

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  