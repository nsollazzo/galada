---
layout: page
title: About
image: 08.jpg
permalink: /about/
---

<h1 align="center"> 📖 Biography 📖 </h1>

☀️ **BY DAY**: *Economics and Business Management Student at University of Milano - Bicocca*
<br>
🌑 **BY NIGHT**: *Freelancer Developer and Bitcoiner*
<br>
🥳 **FOR FUN**: *Digital Artist and Musician*
<br>

Howdy! My name is **Nicholas Sollazzo** and I study **Economics and Business Administration** at the University of Milano-Bicocca and I have a background as a Computer Scientist.
<br>
<br>
I chose this degree course because *"when I grew up I want to be an entrepreneur"*: I knew that there were no real university courses to be an entrepreneur, but this seemed pretty close to me 😉.
<br>
<br>
As a **Computer Scientist at my very core**, I'm **very curious** and very often my brain starts to wonder *why some things works that way* and if they *could be done better*. So I begin to read, watch and listen to every source I'm able to find in order to understad *the first basis from which a thing is known* and then I begin to think of what solutions could be used in order to make it works better.
<br>
<br>
That is why I want to be an entrepreneur. Because **I would like to do something to change the world**. Because I see everyday things that are done fundamentally wrong, like privacy, the environmental protection, financial system, and so much more, and I think I could help to make it right. I could help to improve that.
<br>
That's why I want to be an entrepreneur. To build something to help. Something to create value for every single person on earth. Something to fix what, in my opinion, is wrong or could be done better in this modern age.
<br>
<br>
This is who I am. <br>
This is who I want to be. <br>
This is who I will become. <br>

<h1 align="center">👩‍💻 Follow Me 👨‍💻</h1>

<div>
    <ul class="social-networks list-reset">
        {%- for link in site.social-network-links -%}
        {%- assign curkey = link[0] -%}
        {%- assign element = site.data.SocialNetworks[curkey] -%}
        <li class="social-networks-item">
        {%- if curkey == 'rss' -%}
            <a class="social-networks-link" href="{{ '/feed.xml' | relative_url }}" title="{{ element.name }}">
        {%- elsif curkey == 'yelp' -%}
            <a class="social-networks-link" href="https://{{ site.social-network-links[curkey] }}.yelp.com" title="{{ element.name }}">
        {%- else -%}
            <a class="social-networks-link" href="{{element.baseURL}}{{ site.social-network-links[curkey] }}" title="{{ element.name }}">
        {%- endif -%}
            <i class="ion ion-logo-{{ curkey }}"></i>
        </a>
        </li>
        {%- endfor -%}
    </ul>
</div>