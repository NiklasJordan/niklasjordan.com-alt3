---
layout: default
title: Ahoy
headline: <span class="waving">👋</span> Ahoy
description: I deliver superior digital products, services & experiences for organisations with cause. Sustainable and ethical web. Besides, I'm a budding geoscientist.
intro: I deliver superior <span class="mark">digital products, services & experiences for organisations with cause</span>. Sustainable and ethical web. Besides, I'm a budding <a href="#">geoscientist</a>.
---

You must make prototypes of your service to explore, share and test different designs before you commit to building anything.

You can quickly make and test multiple prototypes and discard the ones that don’t test well.

Making prototypes is important because it:

- improves the usability of your service
- helps you to make sure you’re building the right service for your users
- helps your whole team to get a shared understanding about the future of your service
- allows your team to explore design ideas much faster and at lower risk than using your production code

## Topics, I talk about

- Blinds are not our target group (Accessibility 101)
- Build a sustainable web

## Stuff, I've work on

- I build an <strong>app concept</strong> for a German party which <strong>helps to involve the party base</strong> actively and unconditionally in the election campaign work.
- I've found a plattform that <strong>curating the best design of nonprofit and purpose-driven organizations</strong> from around the world.

## Things, I've written

<ul>
{% for mypost in site.posts %}
  <li><a href="{{ mypost.url | prepend: site.baseurl }}">{{ mypost.title }}</a></li>
{% endfor %}
</ul>
