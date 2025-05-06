---
title: Contact
nav:
  order: 5
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

[Our AMBIOM group](https://www.isas.de/en/research/research-groups?page=1&sort=asc&entry-id=3472c3b8-5b3f-4333-804d-10077327ea02) is part of the [Biospectroscopy Research Department](https://www.isas.de/en/research/research-groups?page=1&entry-id=3472c3b8-5b3f-4333-804d-10077327ea02&sort=asc), at [the Leibniz-Institut für Analytische Wissenschaften – ISAS – e.V.](https://www.isas.de/en).

{%
  include button.html
  type="email"
  text="Email group PI"
  link="jianxu.chen@isas.de"
%}
{%
  include button.html
  text="Find us on Google Maps"
  tooltip="Our location on Google Maps for easy navigation"
  link="https://goo.gl/maps/NmG3sR2fusQmG7AE9"
%}

{% include section.html %}

{% capture col1 %}

{%
  include figure.html
  image="images/isas.png"
  caption="ISAS City"
%}

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="images/dortmund.jpg"
  caption="City of Dortmund"
%}

{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}

{% include section.html dark=true %}

{% capture col1 %}

{% endcapture %}

{% capture col2 %}

{% endcapture %}

{% capture col3 %}

{% endcapture %}

{% include cols.html col1=col1 col2=col2 col3=col3 %}
