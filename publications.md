---
layout: page
title: "Publications"
permalink: /publications/
---

# Publications

Below is a list of our recent research contributions:

{% for paper in site.data.publications %}
- **{{ paper.title }}**  
  {{ paper.authors }}  
  _{{ paper.journal }}, {{ paper.year }}_  
  [Read more]({{ paper.link }})
{% endfor %}

[Explore our research areas →](/research/)
