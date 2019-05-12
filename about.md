---
layout: page
title: About & contact
permalink: /about/
---

<div class="site-contact">

    <h2>Contact</h2>
    <ul class="social-media-list">
    <li>
        <a href="mailto:{{ site.email }}">
        <i class="fa fa-envelope-o"></i>
        <span class="username">{{ site.email }}</span>
        </a>
    </li>

    {% for social in site.social %}
        {% if social.url != null %}
        <li>
        <a href="{{ social.url }}" title="{{ social.desc }}">
            <i class="fa fa-{{ social.icon }}"></i>
            <span class="username">{% if social.username %}{{ social.username }}{% else %}{{ social.name }}{% endif %}</span>
        </a>
        </li>
        {% endif %}
    {% endfor %}

    </ul>
</div>

<h2>About me</h2>


<p>
    My name is Radosław Landowski. I have a great passion to leather goods and handcrafting. I’m full of respect for traditional leathercrafting techniques and I’m totally fascinated with nature.
</p>

<p>
    As a leathercrafter and true nature enthusiast I believe in simplicity. When doing my designs and goods I often think about the words by Marco Pierre White, the great Chef:
</p>

<p class="quotation-element">
    Mother Nature is the true artist and our job as cooks is to allow her to shine
</p>

<p>
    And although these words are intended for cooks, I find them well applicable in leathercrafts as well. Vegetable tanned leather is beautiful on its own – the colour, smell, texture, smooth surface and even small imperfections make it a truly noble material. As a craftsman I try to keep things simple and make sure that the Mother Nature is indeed the true artist and that my work only allows her to fully express herself.
</p>

<p>
    Speaking of the imperfections – I love these the most. A darker area or spot on the surface, veins of the animal creating these subtle lines, little scratches and marks done by biting insects or fights with other animals – this is nature! All of these make up a life of an animal. It’s a history of the living being that must be respected, appreciated and even highlighted properly, just out of respect for the animal.
</p>

<p>
    I find these little defects make truly unique pieces and I never throw away a ‘faulty’ leather piece, I make these imperfections a feature as long as they don’t affect the durability or ergonomics.
</p>

<p>
    That’s my philosphy.
</p>

<style>
    .quotation-element {
        font-size: x-large;
        font-style: italic;
        text-align: center;
    }
</style>


185.199.108.153
185.199.109.153
185.199.110.153
185.199.111.153