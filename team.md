---
title: Team
layout: default
permalink: /team/
tags: [team]
---

<div class="main">
  <div class="container">
    <div class="section text-left">
      <h2>Our Team</h2>
      We are a team of leading experts in blockchain interoperability, security and crypto-economics, distributed across London, Vienna, Edinburgh, Belgrade, and Tokyo.
      <div class="row mt-4">
      {% for user in site.data.bios %}
      <div class="col-md-4 text-center margin-top-small">      
          <a href="{{ user.website }}" target="__blank">
          <img class="profile-image u-round profile-image" src="/../assets/img/profile/{{ user.image }}" alt="{{ user.name }}">
            <h4><b>{{ user.name }}</b></h4>
          </a>
          <h4>{{ user.role }}</h4>
          {% if user.twitter %}
            <a class="" href="https://twitter.com/{{ user.twitter }}" target="_blank">
              <i class="fa fa-twitter"></i>
            </a>&nbsp;
          {% endif%}
          {% if user.github %}
            <a class="" href="https://github.com/{{ user.github }}" target="_blank">
              <i class="fa fa-github"></i>
            </a>&nbsp;
          {% endif%}
          {% if user.scholar %}
            <a class="" href="https://scholar.google.co.uk/citations?user={{ user.scholar }}&hl=en&oi=ao" target="_blank">
              <i class="fa fa-graduation-cap"></i>
            </a>&nbsp;
          {% endif%}
          {% if user.linkedin %}
            <a class="" href="https://www.linkedin.com/in/{{ user.linkedin }}" target="_blank">
              <i class="fa fa-linkedin"></i>
            </a>
          {% endif%}
          <p class="text-justify">
          {{ user.bio }}
          </p>
        </div>
      {% endfor %}
      </div>
    </div>
  </div>
</div>
