---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

Habicht, Isabel M. (2022): Do mothers get lost at the postdoc stage? Event history analysis of psychologists at German universities (1980-2019). Higher Education. https://doi.org/10.1007/s10734-022-00949-y

Habicht, Isabel M.; Schröder, Martin; Lutter, Mark (forthcoming): Female advantage in German sociology. Does accounting for the "leaky pipeline" effect in becoming a tenured university professor make a difference? Soziale Welt.  

Habicht, Isabel M. (2022): Gender differences in the determinants of becoming a tenured professor, obtaining a habilitation, research productivity, and leaving academia in Germany from 1980 − 2019. Doctoral thesis (University of Wuppertal).

Lutter, M., Habicht, I. M., & Schröder, M. (2022). Gender differences in the determinants of becoming a professor in Germany. An event history analysis of academic psychologists from 1980 to 2019. Research Policy, 51(6), 104506. https://doi.org/10.1016/j.respol.2022.104506 

Habicht, I.M., Lutter, M. & Schröder, M. (2021). How human capital, universities of excellence, third party funding, mobility and gender explain productivity in German political science. Scientometrics. https://doi.org/10.1007/s11192-021-04175-8 

Schröder, M., Lutter, M., & <b>Habicht, I. M.</b> (2021). Publishing, signaling, social capital, and gender: Determinants of becoming a tenured professor in German political science. <i>Plos one</i>, 16(1), e0243514. <a href="{{https://doi.org/10.1371/journal.pone.0243514}}">DOI</a>. <a href="{{https://osf.io/afrxk/}}">Data</a>.



{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
