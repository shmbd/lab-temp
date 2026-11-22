---
title: Team
nav:
  order: 3
  tooltip: Scientific officers, fellows, and alumni
---

# {% include icon.html icon="fa-solid fa-users" %}Team

Meet the scientific officers, research fellows, and graduate thesis alumni advancing experimental microbiology, comparative genomics, and bioprocess innovation in the Microbial Biotechnology Division at NIB Bangladesh. Click any member portrait to view their profile and division publications.

{% include section.html %}

## Scientific Officers

{% include list.html data="members" component="portrait" filter="role == 'principal-scientific-officer'" %}
{% include list.html data="members" component="portrait" filter="role == 'senior-scientific-officer'" %}
{% include list.html data="members" component="portrait" filter="role == 'scientific-officer'" %}

{% include section.html background="images/background.jpg" dark=true %}

## Mentorship for Curious, Motivated Minds

We welcome enthusiastic MS/BS thesis students, research fellows, interns, and scientific collaborators eager to develop rigorous skills across wet-lab microbiology and computational genomics at NIB's Savar campus.

{%
  include button.html
  icon="fa-solid fa-user-plus"
  text="Explore Opportunities & Apply"
  link="join"
%}
{%
  include button.html
  icon="fa-regular fa-envelope"
  text="Contact the Division"
  link="contact"
%}

{% include section.html %}

## Research Fellows & Thesis Alumni

Former research fellows and graduate thesis students who trained in the Microbial Biotechnology Division and now contribute across academia and the pharmaceutical sector.

{% include list.html data="members" component="portrait" filter="role == 'research-fellow'" %}
{% include list.html data="members" component="portrait" filter="role == 'thesis-student'" %}
