---
layout: page
title: "Team"
permalink: /team/
---

# Meet Our Team

## Principal Investigator
- **Dr. Shanti Shwarup Mahto**  
  Assistant Professor, Central University of Jharkhand  
  Research Interests: Hydroclimatic studies, Remote Sensing, Climate Science  
  [Google Scholar](#) | [ResearchGate](#) | [Email](mailto:#)

## Research Members
{% for member in site.data.team %}
- **{{ member.name }}** – {{ member.role }}  
  _{{ member.research_area }}_
{% endfor %}

[Join our team →](/opportunities/)
