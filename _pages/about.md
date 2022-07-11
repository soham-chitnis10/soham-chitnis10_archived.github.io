---
permalink: /
title: "About me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am Soham Chitnis, currently a pre-final year student at Birla Institute of Technology and Science,K.K Birla Goa Campus pursuring undergrad in Computer Science. I have keen interest in Machine Learning and Deep Learning. I have worked on Computer Vision Projects. I am a member of [Society for Artificial Intelligence and Deep Learning](https://www.saidl.in/). I am looking to collaborate on Open source and Research projects.

<ul>
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
</ul>