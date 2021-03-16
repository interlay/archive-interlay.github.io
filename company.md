---
title: Company
layout: default
permalink: /company/
tags: [company]
---

<div class="main">
  <div class="container">
    <div class="section text-left">
      <h2> We make DeFi interoperable </h2> 
      <h3>Vision</h3>
      <p>
 We envision a future where blockchains can seamlessly connect and interact, regardless of their design and purpose. Anyone should use any digital currency on any blockchain platform without restrictions.
      </p>
      <h3>Mission</h3>
      <p>
      Our mission is to make Bitcoin useful. Bitcoin holders should easily earn passive income on their BTC holdings by investing into decentralized financial products on any blockchain - without trusting centralized services. 
      </p>

      <h4>
      <b>
        <a href="/contact">
        Contact us <span class="fa fa-angle-right"></span>
        </a>
        </b>
      </h4>      
      <br/>
      
      <h3>Interlay Team</h3>      
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
              <i class="fab fa-twitter"></i>
            </a>&nbsp;
          {% endif%}
          {% if user.github %}
            <a class="" href="https://github.com/{{ user.github }}" target="_blank">
              <i class="fab fa-github"></i>
            </a>&nbsp;
          {% endif%}
          {% if user.scholar %}
            <a class="" href="https://scholar.google.co.uk/citations?user={{ user.scholar }}&hl=en&oi=ao" target="_blank">
              <i class="fas fa-graduation-cap"></i>
            </a>&nbsp;
          {% endif%}
          {% if user.linkedin %}
            <a class="" href="https://www.linkedin.com/in/{{ user.linkedin }}" target="_blank">
              <i class="fab fa-linkedin"></i>
            </a>
          {% endif%}
          <p class="text-justify bio-text">
          {{ user.bio }}
          </p>
        </div>
      {% endfor %}
      </div>
      
      <h4>
      <b>
        <a href="/careers">
        Careers <span class="fa fa-angle-right"></span>
        </a>
        </b>
      </h4>    
      <br/>

      <h3>Advisors</h3>      
      <div class="row mt-4">
      {% for user in site.data.advisors %}
      <div class="col-md-4 text-center margin-top-small">      
          <a href="{{ user.website }}" target="__blank">
          <img class="profile-image u-round profile-image" src="/../assets/img/profile/{{ user.image }}" alt="{{ user.name }}">
            <h4><b>{{ user.name }}</b></h4>
          </a>
          <h4>{{ user.role }}</h4>
          {% if user.twitter %}
            <a class="" href="https://twitter.com/{{ user.twitter }}" target="_blank">
              <i class="fab fa-twitter"></i>
            </a>&nbsp;
          {% endif%}
          {% if user.github %}
            <a class="" href="https://github.com/{{ user.github }}" target="_blank">
              <i class="fab fa-github"></i>
            </a>&nbsp;
          {% endif%}
          {% if user.scholar %}
            <a class="" href="https://scholar.google.co.uk/citations?user={{ user.scholar }}&hl=en&oi=ao" target="_blank">
              <i class="fas fa-graduation-cap"></i>
            </a>&nbsp;
          {% endif%}
          {% if user.linkedin %}
            <a class="" href="https://www.linkedin.com/in/{{ user.linkedin }}" target="_blank">
              <i class="fab fa-linkedin"></i>
            </a>
          {% endif%}
          <p class="text-justify bio-text">
          {{ user.bio }}
          </p>
        </div>
      {% endfor %}
      </div>

    </div>
  </div>
</div>
