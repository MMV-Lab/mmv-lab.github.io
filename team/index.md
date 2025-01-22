---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team


We are building a team with diverse background and expertises, from software enigneering, machine learning, image analysis, data analysis to computational modeling. We are multiple opennings for master students to work as thesis. The topics will be related bioimage analysis and machine learning.

{% include section.html %}

{% include list.html data="members" component="portrait" filter="role == 'pi'" %}
{% include list.html data="members" component="portrait" filter="role == 'postdoc'" %}
{% include list.html data="members" component="portrait" filter="role == 'phd'" %}
{% include list.html data="members" component="portrait" filter="role == 'programmer'" %}
{% include list.html data="members" component="portrait" filter="role == 'master'" %}
{% include list.html data="members" component="portrait" filter="role == 'student'" %}
{% include list.html data="members" component="portrait" filter="role == 'visit'" %}

# {% include icon.html icon="fa-solid fa-users" %}Past Member

{% include list.html data="members" component="portrait" filter="role == 'postdoc_past'" %}
{% include list.html data="members" component="portrait" filter="role == 'phd_past'" %}
{% include list.html data="members" component="portrait" filter="role == 'scientist_past'" %}
{% include list.html data="members" component="portrait" filter="role == 'programmer_past'" %}
{% include list.html data="members" component="portrait" filter="role == 'master_past'" %}
{% include list.html data="members" component="portrait" filter="role == 'student_past'" %}
{% include list.html data="members" component="portrait" filter="role == 'visit_past'" %}


{% include section.html background="images/background.jpg" dark=true %}

JOIN US!! 

{% include section.html %}

# {% include icon.html icon="fa-solid fa-glass-cheers" %} Group Photo

{% capture content %}

{% include figure.html image="images/group_1.jpg" caption="2022 summer retreat in Essen"%}
{% include figure.html image="images/group_2.jpg" caption="2023 summer team-game event"%}
{% include figure.html image="images/group_3.jpg" caption="2023 winter gathering at Christmas market"%}
{% include figure.html image="images/group_4.jpg" caption="2024 summer retreat in Essen"%}

{% endcapture %}

{% include grid.html style="square" content=content %}
