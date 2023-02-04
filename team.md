---
layout: default
---

#  Team

We value diverse opinions on our team and are (primarily) a result of Berkeley's collaborative culture.
Please reach out to any of us if you would like to contribute!

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