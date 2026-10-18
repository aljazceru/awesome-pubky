---
layout: default
title: Research &amp; Proposals - Pubky Directory
permalink: /research-proposals/
---

> Back to the [full directory](./README.md) — pubky.tech

{% capture readme %}{% include_relative README.md %}{% endcapture %}
{% capture nl %}
{% endcapture %}{% assign head = nl | append: "#" %}
{% assign section = readme | split: "(./research-proposals.md)" | last | split: head | first %}
### Research & Proposals
{{ section }}
