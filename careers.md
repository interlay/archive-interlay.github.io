---
title: Careers
layout: default
permalink: /careers/
tags: [careers]
---

<div class="main">
  <div class="container">
    <div class="section">
      <h2>Join us</h2>
      We are looking for talented software engineers and researchers to join our team.
      <div class="row">
        <div class="col-md-12">
          {% for job in site.data.jobs %}
          <div class="card">
            <div class="card-body" data-toggle="modal" data-target="#{{ job.id }}">
              <a href="/careers/#{{ job.id }}">
                <h4><b>{{ job.title }}</b></h4>
                <i>{{ job.hours }}. {{ job.location }}</i>
              </a>
            </div>
          </div>
          {% endfor %}
        </div>
      </div>
      <h3>Perks</h3>
      Probably not the main reason you will choose to come to Interlay, but we try to make coming to work every day just
      a little bit better.
      <div class="row mt-3">
        <div class="col-md-6 text-center">
          <img class="rounded" width="64" src="/assets/img/icons/globe.png">
          <br />
          <b>Remote Office</b>
          <br />
          Work from wherever you like. Meet colleagues all over the world.
        </div>
        <div class="col-md-6 text-center">
          <img class="rounded" width="64" src="/assets/img/icons/stopwatch.png">
          <br />
          <b>Flexible Work Hours</b>
          <br />
          We don't believe in 9-5. Work when you are most productive. There's always someone online - a perk of being
          distributed across time zones.
        </div>
      </div>
      <div class="row mt-3">
        <div class="col-md-6 text-center">
          <img class="rounded" width="64" src="/assets/img/icons/office.png">
          <br />
          <b>Co-working Space</b>
          <br />
          Don't want to work from home? We'll support you with finding a co-working space.
        </div>
        <div class="col-md-6 text-center">
          <img class="rounded" width="64" src="/assets/img/icons/education.png">
          <br />
          <b>Research & Knowledge Transfers</b>
          <br />
          Being a research-driven start-up, we support your training and research interests & organize regular knowledge
          transfer workshops.
        </div>
      </div>
      <div class="row mt-3">
        <div class="col-md-6 text-center">
          <img class="rounded" width="64" src="/assets/img/icons/hack.png">
          <br />
          <b>Hackathons & Challenges</b>
          <br />
          When designing/testing new open source software, we like to participate in hackathons for short sprints for
          fun and PR.
        </div>
        <div class="col-md-6 text-center">
          <img class="rounded" width="64" src="/assets/img/icons/island.png">
          <br />
          <b>Yearly Retreat</b>
          <br />
          We like traveling and hanging out together in real life is awesome. </div>
      </div>
      <h3 class="mt-5">Company Culture</h3>
      Interlay is a <b>fully remote company</b>, distributed across London, Vienna, Edinburgh and Tokyo. This means we
      need to openly communicate as effectively as possible.
      Inspired by <a href="https://about.gitlab.com/blog/2015/04/08/the-remote-manifesto/" target="__blank"
        rel="nofollow">Gitlab's Remote Manifasto</a>, we stick to 7 principles for remote working:
      <br />
      <br />
      <div style="font-size: 1rem; !important">
        {% capture manifesto %}
        {% include remote-manifest.md %}
        {% endcapture %}
        {{ manifesto | unindent | markdownify }}
      </div>
    </div>
  </div>
</div>


{% for job in site.data.jobs %}
<div class="modal fade" id="{{ job.id }}" tabindex="-1" role="dialog">
  <div class="modal-dialog" role="document">
    <div class="modal-content">
      <div class="modal-header">
        <a href="/careers/#{{ job.id }}">
          <h4 class="modal-title"><b> {{ job.title }}</b></h4>
        </a>
        <button type="button" class="close" data-dismiss="modal" aria-label="Close">
          <i class="material-icons">clear</i>
        </button>
      </div>
      <div class="modal-body">
        {% capture manifesto %}
        {% include {{ job.file }} %}
        {% endcapture %}
        {{ manifesto | unindent | markdownify }}
        <br />
      </div>
      <div class="modal-footer">
        <a href="mailto:careers@interlay.io?subject=Application - {{ job.title }} - via Interlay Careers" target="__blank">
          <button class="btn btn-block btn-primary">
            <i class="material-icons">library_books</i> Apply (CV + short statement)
          </button>
        </a>
        <button type="button" class="btn btn-block" data-dismiss="modal">Close</button>
      </div>
    </div>
  </div>
</div>
{% endfor %}