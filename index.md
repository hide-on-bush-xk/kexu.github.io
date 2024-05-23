---
layout: home
title: Home
landing-title: 'Hi, my name is Ke Xu'
description: 'null'
image: null
author: Ke Xu
show_tile: false
---

<section>

    <div class="contact-method">
        <span class="icon alt fa-envelope"></span>
        <h3>Email</h3>
        <a href="mailto:{{ site.email }}">{{ site.email }}</a>
    </div>
</section>

<section>

    <div class="contact-method">
        <span class="icon alt fa-phone"></span>
        <h3>Phone</h3>
        <a href="tel:{{ site.phone }}">{{ site.phone }}</a>
    </div>
</section>

<section>

    <div class="contact-method">
        <span class="icon alt fa-home"></span>
        <h3>Address</h3>
        <span>
        {% if site.street_address %}
            {{ site.street_address }}<br />
        {% endif %}
        {% if site.city %}
            {{ site.city }},
        {% endif %}
        {% if site.state %}
            {{ site.state }} 
        {% endif %}
        {% if site.zip_code %}
            {{ site.zip_code }}<br />
        {% endif %}
        {% if site.country %}
            {{ site.country }}
        {% endif %}
        </span>
    </div>
</section>
