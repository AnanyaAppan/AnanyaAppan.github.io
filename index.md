---
layout: default
title: About
---
<section class="profile">
  <img class="avatar" src="{{ site.author.photo | relative_url }}" alt="{{ site.author.name }}">
  <div>
    <h1>{{ site.author.name }}</h1>
    <p class="affil">
      {{ site.author.position }}<br>
      {{ site.author.university }}
    </p>
    {% include social.html %}
  </div>
</section>

<div markdown="1">
I am a fourth year computer science PhD student at the University of Illinois at Urbana-Champaign. I am interested,
broadly, in cryptography, and specifically, in secure multi-party computation. I am lucky to have two
kind and caring co-advisors: [David Heath](https://daheath.web.illinois.edu) and
[Ling Ren](https://sites.google.com/view/renling). I was previously advised by Professor
[Ashish Choudhury](https://sites.google.com/view/ashish-choudhury) at IIIT Bangalore, to whom I am
ever grateful for introducing me to cryptography and research.

What I love the most about research is the absurd assurance I feel when I get the wrong solution,
and the complete lack of expectation I have when I finally get the right one :) Seeing the final
draft of a paper I have co-authored is also a very special feeling.
</div>

<p><a href="{{ '/research/' | relative_url }}">Publications &rarr;</a></p>
