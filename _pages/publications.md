---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

Research
------

Suryo Prabowo, A. (2022). "Budget Process and Budget Structure under the COVID-19 Pandemic in Indonesia.", In Giovanna Dabbicco et al. (Eds), Public Sector Accounting, Financial Accountability and Viability in Times of Crisis, Palgrave Macmillan. https://doi.org/10.1007/978-3-031-04745-9_2

Joyce, P.G. and Aichiro Suryo Prabowo. (2020), "Government responses to the coronavirus in the United States: immediate remedial actions, rising debt levels and budgetary hangovers", Journal of Public Budgeting, Accounting & Financial Management, Vol. 32 No. 5, pp. 745-758. https://doi.org/10.1108/JPBAFM-07-2020-0111

Suryo Prabowo, A. (2019), “Performance Budgeting in Indonesia: Brief History, Progress, and Lessons Learned.” In Ho, Alfred T., Maarten de Jong, and Zaozao Zhao (Eds.), Performance Budgeting Reforms: Theories and International Practices, ch. 11. New York: Routledge. https://doi.org/10.4324/9781351055307-11


Working Papers
------

The Fiscal Impact of Flood Disasters in State Government

Do governments pay attention to hurricanes more at present than in the past? A textual analysis of budget documents

Disaster Risk Disclosure: Evidence from U.S. State Governments

Determinants of State Research Spending: Theory and Evidence (with Thomas Luke Spreen)


{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
