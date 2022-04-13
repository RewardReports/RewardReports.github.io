---
layout: default
---

# Workshop Organizers

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
</div>

# Volunteers

We are indebted to our 2021 workshop volunteers!

<div class="container">
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

# Reviewers

In addition to the workshop organizers, our workshop reviewer comittee includes the following members:
<a target="blank" href="https://researchers.uq.edu.au/researcher/24776">Archie Chapman</a>, 
<a target="blank" href="https://simons.berkeley.edu/people/daniela-cialfi">Daniela Cialfi</a>, 
<a target="blank" href="https://people.eecs.berkeley.edu/~sarahdean/">Sarah Dean</a>,
<a target="blank" href="http://tttor.github.io/">Vektor Dewanto</a>, 
<a target="blank" href="https://www.admscentre.org.au/henry-fraser/">Henry Fraser</a>, 
<a target="blank" href="https://au.linkedin.com/in/camerondgordon">Cameron Gordon</a>, 
<a target="blank" href="https://www.linkedin.com/in/xiaoguo-neuhkuuq">Xiao Guo</a>, 
<a target="blank" href="https://www.natolambert.com/">Nathan Lambert</a>, and
<a target="blank" href="https://research.qut.edu.au/adms/people/abdul-obeid/">Abdul Obeid</a>.
