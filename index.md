---
layout: default
title: Home | Social AI and Multi-Agent Systems | Nirav Ajmeri's Group at Bristol
---
## Welcome to Social AI and Multi-Agent Systems Research at Bristol!

We are a team of researchers advancing foundational AI for the societal good, focusing on the development of ethical multi-agent systems. 
Our work encompasses intelligent agents and normative multi-agent systems, multi-agent reinforcement learning, and graph-based approaches, all while integrating normative principles to ensure that AI systems align with societal norms and values.

Our research seeks to facilitate interactions between computational agents and social entities, such as humans and organizations, with a strong emphasis on promoting prosocial behaviour and ensuring equitable outcomes.

We are based in the [School of Computer Science](https://www.bristol.ac.uk/science-engineering/schools/computer-science/) at the [University of Bristol](https://www.bristol.ac.uk). 
Our team is part of the federated [Intelligent Systems Labs](https://www.bristol.ac.uk/research/groups/intelligent-systems/), which comprises several units focussing on AI, machine learning, and data science research. We are affiliated with the [Collective Dynamics lab](https://uob-colldyn.github.io/) and the [AI lab](https://uob-ai-lab.github.io/) units.

To learn more about our research and contributions, please explore our publications. If you are looking for a specific paper, tool, or dataset, feel free to reach out to [Nirav Ajmeri](https://niravajmeri.github.io). 


<!--
<div id="imageCarousel" class="carousel slide" data-ride="carousel">
  <div class="carousel-inner">
    <div class="carousel-item active">
      <img src="/assets/images/carousel/priene.png" class="d-block w-100" alt="Operationalising Ethics for Prosociality | Schematic of a Norm-Learning Agent">
      <div class="carousel-caption d-none d-md-block">
        <p>Schematic of Socially Intelligent Norm-Learning Agent</p>
      </div>
    </div>
    <div class="carousel-item">
      <img src="/assets/images/carousel/top.png" class="d-block w-100" alt="Generalising Multi-Domain Graph Models | Topology Only Pre-Training">
      <div class="carousel-caption d-none d-md-block">
        <p>Schematic for Topology Only Pre-Training Models.</p>
      </div>
    </div>
  </div>
  <a class="carousel-control-prev" href="#imageCarousel" role="button" data-slide="prev">
    <span class="carousel-control-prev-icon" aria-hidden="true"></span>
    <span class="sr-only">Previous</span>
  </a>
  <a class="carousel-control-next" href="#imageCarousel" role="button" data-slide="next">
    <span class="carousel-control-next-icon" aria-hidden="true"></span>
    <span class="sr-only">Next</span>
  </a>
</div>-->

<h2>Meet the Team</h2>

<div class="team-container">
  {% for member in site.data.team.teams %}
<div class="team-member">
  <img src="/assets/images/team/{{ member.photo }}" alt="{{ member.name }}" style="width: 150px; border-radius: 8px;">
  <h5><a href="{{ member.webpage }}">{{ member.name }}</a></h5>
  <p>{{ member.title }}</p>
  {% if member.keywords %}<p>Interests: <em>{{ member.keywords | join: ", " }}</em></p> {% endif %}
  <p>
    {% if member.email %} <a href="mailto:{{ member.email }}"><img src="/assets/images/email.png" style="width:24px;"/></a> {% endif %}
    {% if member.google_scholar %} <a href="{{ member.google_scholar }}"><img src="/assets/images/google_scholar.png" style="width:24px;"/></a> {% endif %} 
    {% if member.orcid %} <a href="{{ member.orcid }}"><img src="https://orcid.org/assets/icons/favicon.ico" style="width:24px;"/></a> {% endif %}
  </p>
</div>
  {% endfor %}
</div>
