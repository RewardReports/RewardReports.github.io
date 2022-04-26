---
layout: default
---

#  Building Accountable and Transparent RL

**This RLDM 2022  Workshop is on Saturday June 11th from 1:00-5:00pm EST.**

_Workshop schedule and confirmed attendees forthcoming soon_

## Motivation

When RL is used in societally relevant domains, practitioners must balance contested values, while anticipating and responding to resulting downstream effects. 
This will require documenting the behavior of RL systems over time, both in relation to design choices and dynamic effects. 
In this workshop, we will survey existing approaches to AI documentation, discuss the unique challenges posed by RL deployments, and introduce a proposal for "Reward Reports": living documents that demarcate design choices and track system behavior. 
The majority of the workshop will be interactive, with participants trying out and critiquing methods of documentation for real or imagined RL applications.


## Format -- The (Un)Workshop
We intend for this workshop to be a generative and interactive space for participants to try out and critique our Reward Reports proposal. As such, activities will be centered around doing and sharing in small groups, punctuated by periodic larger group discussions. We will begin with a round of introductions to create a friendly environment. After a presentation about the Reward Reports proposal by the organizers, participants will form small groups (2-3) based on target RL applications (real or imagined). Much of the workshop time will entail actually writing Reward Report-style documentation. Periodically, participants will form medium-sized groups based on application domain to discuss challenges or give feedback on drafts. Finally, we will conclude with a workshop-wide discussion on the practicality of the Reward Reports framework and elements that may be missing. We hope that by the end of the workshop, there will be two concrete outputs: a rich set of example RRs, and a list of refinements for the Reward Reports framework.

To learn more about Reward Reports, see the [Reward Reports paper](/assets/reward_reports_for_rl.pdf), the [CLTC RL Risks Whitepaper](http://arxiv.org/abs/2202.05716), or the [github repo](https://github.com/RewardReports/reward-reports) with a template.


# How to participate

Register for the Multi-disciplinary Conference on Reinforcement Learning and Decision Making ([RLDM](https://rldm.org/)).
<!-- Contact the organizors  -->

Send us a message with any questions!

<iframe src="https://docs.google.com/forms/d/e/1FAIpQLSdtARZRCD80KADgF9uADxlxgZ-e5ub4es7ETM4iHXcSAJQUpg/viewform?embedded=true" width="100%" height="350" frameborder="0" marginheight="0" marginwidth="0">Loading…</iframe>


# Workshop Organizers

<div class="row justify-content-center">
    {% for panelist in site.data.organizers %}
        <div class="text-center speaker">
            <img src="{{ panelist.image }}" class="speaker-img" />

            <div class="break"></div>

            {% if panelist.website %}
            <a href="{{ panelist.website }}" target="_blank" >
                {{ panelist.name }}
            </a>
            {% else %}
                {{ panelist.name }}
            {% endif %}

            <div class="break"></div>

            <div class="speaker-affiliation">
            {% if panelist.affiliation %}
                {{ panelist.affiliation }}
            {% endif %}
            </div>
        </div>
    {% endfor %}
</div>

