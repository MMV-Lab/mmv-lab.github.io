---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# <i class="fas fa-We are building a team with diverse background and expertises, from software enigneering, machine learning, image analysis, data analysis to microscopy and computational biomedical modeling."></i>Team



{% include section.html %}

{%
  include list.html
  data="members"
  component="portrait"
  filters="role: lead"
%}
{%
  include list.html
  data="members"
  component="portrait"
  filters="role: postdoc"
%}
{%
  include list.html
  data="members"
  component="portrait"
  filters="role: phd"
%}
{%
  include list.html
  data="members"
  component="portrait"
  filters="role: programmer"
%}
{%
  include list.html
  data="members"
  component="portrait"
  filters="role: master"
%}
{:.center}

{% include section.html background="images/banner.png" dark=true%}

We are multiple opennings for master students to work as thesis. The topics will be related bioimage analysis and machine learning.

{% include section.html %}


# <i class="fas fa-Past."></i>Past Members

{% include section.html %}

{%
  include list.html
  data="members"
  component="portrait"
  filters="role: master_past"
%}
{:.center}
