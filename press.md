---
title: Press
permalink: /press/
layout: default
tags: [press]
---

<div class="main">
    <div class="container">
        <div class="section text-left">
            <h2>Press</h2>
            <h4>For press inquiries, please contact <a href="mailto:contact@interlay.io?subject=Press Inquiry">contact@interlay.io</a></h4>
            <h3>Press Coverage</h3>
            {% for post in site.data.press %}
            <div class="card">
                <a href="{{ post.url}}">
                    <div class="card-body">
                        <h4><strong>{{ post.title }}</strong></h4>
                        <h4>{{ post.author }}</h4>
                        <p>{{ post.summary }}</p>
                        <div class="row">
                            <div class="col-lg-10">
                                {{ post.date }}
                            </div>
                            <div class="col-lg-2 text-right">
                                <b>Read article</b>
                            </div>
                        </div>
                    </div>
                </a>
            </div>
            {% endfor %}
        </div>
    </div>
</div>