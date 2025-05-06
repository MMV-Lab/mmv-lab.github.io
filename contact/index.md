---
title: Contact
nav:
  order: 5
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

<<<<<<< HEAD
[Our AMBIOM group](https://www.isas.de/en/research/research-groups?page=1&sort=asc&entry-id=3472c3b8-5b3f-4333-804d-10077327ea02) is part of the [Biospectroscopy Research Department](https://www.isas.de/en/research/research-groups?page=1&entry-id=3472c3b8-5b3f-4333-804d-10077327ea02&sort=asc), at [the Leibniz-Institut für Analytische Wissenschaften – ISAS – e.V.](https://www.isas.de/en).
=======
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor
incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis
nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
>>>>>>> template/main

{%
  include button.html
  type="email"
<<<<<<< HEAD
  text="Email group PI"
  link="jianxu.chen@isas.de"
%}
{%
  include button.html
  text="Find us on Google Maps"
  tooltip="Our location on Google Maps for easy navigation"
  link="https://goo.gl/maps/NmG3sR2fusQmG7AE9"
=======
  text="jane@smith.com"
  link="jane@smith.com"
%}
{%
  include button.html
  type="phone"
  text="(555) 867-5309"
  link="+1-555-867-5309"
%}
{%
  include button.html
  type="address"
  tooltip="Our location on Google Maps for easy navigation"
  link="https://www.google.com/maps"
>>>>>>> template/main
%}

{% include section.html %}

{% capture col1 %}

{%
  include figure.html
<<<<<<< HEAD
  image="images/isas.png"
  caption="ISAS City"
=======
  image="images/photo.jpg"
  caption="Lorem ipsum"
>>>>>>> template/main
%}

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
<<<<<<< HEAD
  image="images/dortmund.jpg"
  caption="City of Dortmund"
=======
  image="images/photo.jpg"
  caption="Lorem ipsum"
>>>>>>> template/main
%}

{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}

{% include section.html dark=true %}

{% capture col1 %}
<<<<<<< HEAD

{% endcapture %}

{% capture col2 %}

{% endcapture %}

{% capture col3 %}
QQQQQQQ
=======
Lorem ipsum dolor sit amet  
consectetur adipiscing elit  
sed do eiusmod tempor
{% endcapture %}

{% capture col2 %}
Lorem ipsum dolor sit amet  
consectetur adipiscing elit  
sed do eiusmod tempor
{% endcapture %}

{% capture col3 %}
Lorem ipsum dolor sit amet  
consectetur adipiscing elit  
sed do eiusmod tempor
>>>>>>> template/main
{% endcapture %}

{% include cols.html col1=col1 col2=col2 col3=col3 %}
