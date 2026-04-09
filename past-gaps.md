---
layout: default
title: Past GAPS Workshops
---
<div class="docs-section no-top-border" id="past">
  <div class="docs-header">Past GAPS Workshops</div>
  
{% assign events = site.data.events | sort: "year" | reverse %}
{% for event in events %}
   <ul>
     <li><a href="{{ event.link }}" target="_blank"><b>GAPS {{ event.year }}</b></a> was held at <i>{{ event.venue }}</i> by {{ event.organiser }}.</li>
   </ul>
{% endfor %}
</div>
