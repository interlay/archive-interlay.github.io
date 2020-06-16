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
          <div class="card">
            <div class="card-body" data-toggle="modal" data-target="#vp-operations">
              <a href="javascript:void(0)">
                <h3>VP Operations</h3>
                <i>Full time. Remote, preferably based in UK</i>
              </a>
            </div>
          </div>
          <div class="card">
            <div class="card-body" data-toggle="modal" data-target="#frontend-engineer">
              <a href="javascript:void(0)">
                <h3>Frontend Engineer (React + TypeScript)</h3>
                <i>Full time. Remote, preferably based in UK</i>
              </a>
            </div>
          </div>
          <div class="card">
            <div class="card-body" data-toggle="modal" data-target="#software-engineer">
              <a href="javascript:void(0)">
                <h3>Software Engineer (Rust)</h3>
                <i>Full time. Remote, preferably based in UK</i>
              </a>
            </div>
          </div>
        </div>
      </div>
      <h3>Perks</h3>
      Probably not the main reason you will choose to come to Interlay, but we try to make coming to work every day just a little bit better.
      <div class="row mt-3">
        <div class="col-md-6 text-center">
            <img class="rounded" width="64" src="/assets/img/icons/globe.png">
            <br/>
          <b>Remote Office</b> 
          <br/>
            Work from wherever your like. Meet colleagues all over the world.
        </div>
        <div class="col-md-6 text-center">
            <img class="rounded" width="64" src="/assets/img/icons/stopwatch.png">
            <br/>
          <b>Flexible Work Hours</b> 
          <br/>
            We don't believe in 9-5. Work when you are most productive. There's always someone online - a perk of being distributed across time zones. 
        </div>
      </div>
      <div class="row mt-3">
        <div class="col-md-6 text-center">
            <img class="rounded" width="64" src="/assets/img/icons/office.png">
            <br/>
          <b>Co-working Space</b> 
          <br/>
            Don't want to work from home? We'll support you with finding a co-working space. 
        </div>
        <div class="col-md-6 text-center">
            <img class="rounded" width="64" src="/assets/img/icons/education.png">
            <br/>
          <b>Research & Knowledge Transfers</b> 
          <br/>
            Being a research-driven start-up, we support your training and research interests & organize regular knowledge transfer workshops.         
          </div>
      </div>
      <div class="row mt-3">
        <div class="col-md-6 text-center">
            <img class="rounded" width="64" src="/assets/img/icons/hack.png">
            <br/>
          <b>Hackathons & Challenges</b> 
          <br/>
            When designing/testing new open source software, we like to participate in hackathons for short sprints for fun and PR.
        </div>
        <div class="col-md-6 text-center">
            <img class="rounded" width="64" src="/assets/img/icons/island.png">
            <br/>
          <b>Yearly Retreat</b> 
          <br/>
            We like traveling and hanging out together in real life is awesome.          </div>
      </div>
      <h3 class="mt-5">Company Culture</h3>
        Interlay is a <b>fully remote company</b>, distributed across London, Vienna, Edinburgh and Tokyo. This means we need to openly communicate as effectively as possible.
        Inspired by <a href="https://about.gitlab.com/blog/2015/04/08/the-remote-manifesto/" target="__blank" rel="nofollow">Gitlab's Remote Manifasto</a>, we stick to 7 principles for remote working:
        <br/>
        <br/>
        <div style="font-size: 1rem; !important">
        {% capture manifesto %}
          {% include remote-manifest.md %}
        {% endcapture %}
        {{ manifesto | unindent | markdownify }}
        </div>
      </div>
      
  </div>
</div>

<div class="modal fade" id="vp-operations" tabindex="-1" role="dialog">
  <div class="modal-dialog" role="document">
    <div class="modal-content">
      <div class="modal-header">
        <h4 class="modal-title"><b>VP Operations</b></h4>
        <button type="button" class="close" data-dismiss="modal" aria-label="Close">
          <i class="material-icons">clear</i>
        </button>
      </div>
      <div class="modal-body">
       {% capture manifesto %}
          {% include jobs/vp-operations.md %}
        {% endcapture %}
        {{ manifesto | unindent | markdownify }}
        <br/>
      </div>
      <div class="modal-footer">
        <a href="mailto:careers@interlay.io?subject=Application - VP Operations" target="__blank">
          <button class="btn btn-block btn-primary">
            <i class="material-icons">library_books</i> Apply (CV + short statement)
          </button>
        </a>
        <button type="button" class="btn btn-block" data-dismiss="modal">Close</button>
      </div>
    </div>
  </div>
</div>

<div class="modal fade" id="frontend-engineer" tabindex="-1" role="dialog">
  <div class="modal-dialog" role="document">
    <div class="modal-content">
      <div class="modal-header">
        <h4 class="modal-title"><b>Frontend Engineer (React + TypeScript)</b></h4>
        <button type="button" class="close" data-dismiss="modal" aria-label="Close">
          <i class="material-icons">clear</i>
        </button>
      </div>
      <div class="modal-body">
       {% capture manifesto %}
          {% include jobs/frontend-engineer.md %}
        {% endcapture %}
        {{ manifesto | unindent | markdownify }}
        <br/>
      </div>
      <div class="modal-footer">
        <a href="mailto:careers@interlay.io?subject=Application - Frontend Engineer" target="__blank">
          <button class="btn btn-block btn-primary">
            <i class="material-icons">library_books</i> Apply (CV + short statement)
          </button>
        </a>
        <button type="button" class="btn btn-block" data-dismiss="modal">Close</button>
      </div>
    </div>
  </div>
</div>

<div class="modal fade" id="software-engineer" tabindex="-1" role="dialog">
  <div class="modal-dialog" role="document">
    <div class="modal-content">
      <div class="modal-header">
        <h4 class="modal-title"><b>Software Engineer (Rust)</b></h4>
        <button type="button" class="close" data-dismiss="modal" aria-label="Close">
          <i class="material-icons">clear</i>
        </button>
      </div>
      <div class="modal-body">
       {% capture rust %}
          {% include jobs/software-engineer-rust.md %}
        {% endcapture %}
        {{ rust | unindent | markdownify }}
        <br/>
      </div>
      <div class="modal-footer">
        <a href="mailto:careers@interlay.io?subject=Application - Software Engineer" target="__blank">
          <button class="btn btn-block btn-primary">
            <i class="material-icons">library_books</i> Apply (CV + short statement)
          </button>
        </a>
        <button type="button" class="btn btn-block" data-dismiss="modal">Close</button>
      </div>
    </div>
  </div>
</div>
