---
layout: archive
title: "Experience"
permalink: /experience/
author_profile: true
---

<!-- <ul style="list-style-type:none">
{% for item in site.data.workexp.experiences %}
<li class="a">
  <table class="a"><tr>
  <td class="a" width="20%"><img class="padded-image" src="/images/{{ item.img-path }}" alt="{{ item.name }}" style="width:100%"></td>
  <td class="a" width="80%">
  <span class="designation">{{ item.designation }}</span><br>
  <a class="company" href="{{ item.url }}" target="_blank">{{ item.name }}</a><br>
  <span class="date">{{item.date}}</span><br>
  <p class="desc">
  <br>
  {{item.desc}}
  </p><br>
  </td>
  </tr></table>
  </li>
{% endfor %}
</ul> -->
{% include base_path %}

{% for item in site.data.workexp.experiences %}
    <!-- <img src="/images/{{item.img-path}} style="width:100%">
    <span class="designation">{{ item.designation }}</span><br>
    <a class="company" href="{{ item.url }}" target="_blank">{{ item.name }}</a><br>
    <span class="date">{{item.date}}</span><br>
    <p class="desc">
    <br>
    {{item.desc}}
    </p><br> -->
{% endfor %}