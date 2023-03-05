---
layout: archive
title: "Experience"
permalink: /experience/
author_profile: true
---


{% include base_path %}

{% for item in site.data.workexp.experiences %}
    <img src="/images/{{item.img-path}} style="width:100%">
    <span class="designation">{{ item.designation }}</span><br>
    <a class="company" href="{{ item.url }}" target="_blank">{{ item.name }}</a><br>
    <span class="date">{{item.date}}</span><br>
    <p class="desc">
    <br>
    {{item.desc}}
    </p><br>
{% endfor %}