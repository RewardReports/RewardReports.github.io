---
layout: default
---

# Confirmed speakers and panelists

<div class="row justify-content-center">
    {% for panelist in site.data.speakers %}
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

