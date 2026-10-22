---
layout: single
title: "My Group"
permalink: /my-group/
author_profile: true
---

We are a small research group at the [Global Health Program](https://ghp.ntu.edu.tw/) and the [Institute of Epidemiology and Preventive Medicine](https://epm.ntu.edu.tw/web/index/index.jsp), College of Public Health, National Taiwan University. We analyze infectious disease outbreaks while they unfold, estimate how pathogens spread, and turn the results into evidence that public health agencies can use. NTU students interested in joining us can find details on the [Opportunities](/opportunities/) page.

During the semester the group meets every Thursday at 12:30 in Room 545 of the College of Public Health for outbreak news, progress reports and practice talks. Visitors are welcome; please email ahead.

## Current members

{% include group-members.html %}

## Alumni

<ul class="alumni-list">
{% for m in site.data.members.alumni %}
  <li><strong>{{ m.name }}</strong>, {{ m.role }}{% if m.details and m.details != '' %}. {{ m.details }}{% endif %}</li>
{% endfor %}
</ul>

{% include group-photos.html %}
