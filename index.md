---
layout: default
---


<!-- <span class="click-to-join">[>> Click here to join the workshop live-stream <<](https://neurips.cc/virtual/2021/workshop/21864)</span> -->

<!-- <span class="click-to-join-sub">(must be registered for NeurIPS and logged-in!)</span> -->

<h4 class="text-center"> <strong> Join us at our workshop on Building Accountable and Transparent RL</strong>, at the <a href="https://rldm.org"> The Multi-disciplinary Conference on Reinforcement Learning and Decision Making
          (RLDM)</a> June 11th, 2022</h4>

Building on the documentation frameworks for "model cards" and "datasheets" proposed by Mitchell et al. and Gebru et al., we argue the need for Reward Reports for AI systems. In a whitepaper recently published by the Center for Long-Term Cybersecurity, we introduced Reward Reports as living documents for proposed RL deployments that demarcate design choices. However, many questions remain about the applicability of this framework to different RL applications, roadblocks to system interpretability, and the resonances between deployed supervised machine learning systems and the sequential decision-making utilized in RL. At a minimum, Reward Reports are an opportunity for RL practitioners to deliberate on these questions and begin the work of deciding how to resolve them in practice.

To learn more about Reward Reports, see the 
          <a href="https://arxiv.org/abs/2204.10817"> Reward Reports paper</a>, the
          <a href="http://arxiv.org/abs/2202.05716"> CLTC RL Risks Whitepaper</a> , or the 
          <a href="https://github.com/RewardReports/reward-reports">github repo</a> with a template.

# Designers

<div class="container">
	{% for organizer in site.data.organizers %}
    <div class="organizer row">
        <div class="col-md-auto text-center">
            <img src="{{ organizer.image }}" class="organizer-img" />
            <div class="break"></div>
            {% if organizer.website %}
            <a href="{{ organizer.website }}" target="_blank" >
                {{ organizer.name }}
            </a>
            {% else %}
                {{ organizer.name }}
            {% endif %}
        </div>
        <div class="organizer-bio col">{{ organizer.bio }}</div>
    </div>
    {% endfor %}
    {% for volunteer in site.data.volunteers %}
    <div class="organizer row">
        <div class="col-md-auto text-center">
            <img src="{{ volunteer.image }}" class="organizer-img" />
            <div class="break"></div>
            {% if volunteer.website %}
            <a href="{{ volunteer.website }}" target="_blank" >
                {{ volunteer.name }}
            </a>
            {% else %}
                {{ volunteer.name }}
            {% endif %}
        </div>
        <div class="organizer-bio col">{{ volunteer.bio }}</div>
    </div>
    {% endfor %}
</div>