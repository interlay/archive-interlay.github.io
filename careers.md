---
title: Careers
layout: default
permalink: /careers/
tags: [careers]
---

<div class="main">
  <div class="container">
    <div class="section">
    <h2>We are hiring!
      </h2>
      We are looking for talented software engineers and researchers to join our team!
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
            <div class="card-body" data-toggle="modal" data-target="#rust-se">
              <a href="javascript:void(0)">
                <h3>Software Engineer (Rust)</h3>
                <i>Full time. Remote, preferably based in UK</i>
              </a>
            </div>
          </div>
        </div>
      </div>
      <div class="row">
        <div class="col-md-12">
          <h3>About Interlay</h3>
         At Interlay, we envision a future where permissioned and permissionless blockchains, regardless of design and purpose, can seamlessly connect and interact. From trustless loans to decentralized derivatives & exchanges, from off-chain payment protocols to application-specific ledgers: anyone should use any digital currency on any blockchain platform.
         <br/>
         <br/>
        <h4>Our Tech</h4>
        The open-source XCLAIM framework allows users to move assets across public/permissionless blockchains such as Bitcoin and Ethereum in a trustless manner. Enterprises, on the other hand, can utilize XCLAIM to execute settlements across different permissioned ledgers, choosing from a palette of possible trust models based on use case and required security. To fully exploit the benefits of interoperability, Interlay is building a decentralized trading platform for cross-chain derivative trading on top of XCLAIM (e.g. BTC/ETH, BTC/DAI and BTC/DOT).
        <br/>
        <br/>
        Check out our code at <a href="https://github.com/interlay" target="__blank"><u>github.com/interlay</u></a>
        <br/>
        <br/>
        <h4>Company Culture</h4>
        Interlay was founded by Imperial College London PhDs, who have been working on blockchain security and game theory for the past 5 years. As such, at Interlay we take a research-driven approach: our product designs are bleeding-edge tech and are backed by peer-reviewed, top-tier scientific publications. 
        <br/>
        <br/>
        Interlay is a <strong>fully remote company</strong>, distributed across London, Vienna, Edinburgh and Tokyo. This means we need to openly communicate as effectively as possible.
        Inspired by <a href="https://about.gitlab.com/blog/2015/04/08/the-remote-manifesto/" target="__blank" rel="nofollow">Gitlab's Remote Manifasto</a>, we stick to 7 principles for remote working:
                <br/>
        <br/>
        {% capture manifesto %}
          {% include remote-manifest.md %}
        {% endcapture %}
        {{ manifesto | unindent | markdownify }}
        <br/>
        <br/>
        </div>
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

<div class="modal fade" id="rust-se" tabindex="-1" role="dialog">
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
