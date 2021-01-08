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
      <h4>Our Vision</h4>
      <p>
      We envision a future where blockchains can seamlessly connect and interact, regardless of their design and purpose. Anyone should use any digital currency on any blockchain platform without restrictions. Our mission is to build a <strong>fair, decentralized, zero-trust cross-chain settlement layer</strong>, “a network to connect them all”.
      </p>
      <h4>Our Business</h4>
      <p>
      We started by building infrastructure of tomorrow's interoperable blockchain ecosystem: trustless cross-chain bridges. On top, we are building cross-chain DeFi products that unlock liquidity and new features across platforms. 
      </p>

      <h5>
      <b>
        <a href="/contact">
        Contact us <span class="fa fa-angle-right"></span>
        </a>
        </b>
      </h5>      
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
      
      <h5>
      <b>
        <a href="/careers">
        Careers <span class="fa fa-angle-right"></span>
        </a>
        </b>
      </h5>    
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
