---
title: REST vs SOAP vs GraphQL
tags: [networking]
style: fill
color: secondary
description: This weekend I will define and compare REST, SOAP, and GraphQL..
---

<br>

### Introduction

In the late 1990s and early 2000s, two different design models became the norm in exposing data publicly.

1. **SOAP (Simple Object Access Protocol)** is an actual protocol that provides you with stricter detail about what an API does. This design model is suitable within most enterprise environment due to its solid, reliable pattern.

2. **REST (REpresentational State Transfer)** is used for public APIs and is ideal for fetching data from the web. It's much lighter and closer to the HTTP specification than SOAP. **REST** style of delivering APIs is relying on the HTTP specifications the web is built upon.

There's a new design model in town called **GraphQL** which is created by Facebook. **GraphQL** is very flexible query language for APIs, where the clients decide exactly what they want to fetch from the server instead of the server deciding what to send. This model starts with building a schema which is hard as it requires strong typing in the Schema Definition Language.

{% include elements/figure.html url="/assets/img/posts/api_timeline.png"%}

<figcaption class="figure-caption text-center">Source by: <a href="https://twitter.com/robdcrowley?lang=en">Rob Crowley</a></figcaption>

<br>

### Comparison

**SOAP** is troublesome but its rich security features remain irreplaceable for billing operations, booking systems, and payments.

**REST** has the highest abstraction and best modeling of the API but a downside is if you're working on mobile.

**GraphQL** is a big step forward in terms of data fetching but not everyone has enough time and effort to building schema.

<br>
Four major API styles compared:

{% include elements/figure.html url="/assets/img/posts/api_styles.png"%}

<br>

Check out the video about the comparison if prefer watching:

{% include elements/video.html id="NFw0HznpLlM" %}

<br>

**See also:**

- [API 101: SOAP vs REST](https://blog.postman.com/soap-vs-rest/)
- [Introduction to GraphQL](https://graphql.org/learn/)
