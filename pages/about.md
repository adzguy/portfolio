---
layout: page
title: About
permalink: /about/
weight: 3
---

# **About Me**

Hi I am **{{ site.author.name }}**,<br>
I have a BS degree in Computer Science. I worked in a startup company as a Web Developer. I designed a web interface and site graphics and determined client needs for company site. Currently I develop iOS applications. I have interests in creating Machine Learning models to use in iOS applications. Thanks for visiting my website!

<div class="row">
{% include about/skills.html title="Programming Skills" source=site.data.programming-skills %}
{% include about/skills.html title="Other Skills" source=site.data.other-skills %}
</div>

<div class="row">
{% include about/timeline.html %}
</div>
