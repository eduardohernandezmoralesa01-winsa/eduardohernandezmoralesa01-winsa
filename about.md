---
layout: default
title: Acerca de / Bitácora de Investigación
permalink: /about/
---

# Research Log: Breakthroughs, Theory & Results

This is GSRL's dynamic updates space. Here, Eduardo Hernández-Morales periodically publishes laboratory simulation progress, ongoing mathematical theory development, preprints, and real-time control algorithm results.

## Recent Entries

{% for post in site.posts %}
<div class="post-entry" style="margin-bottom: 24px; padding: 16px; border: 1px solid rgba(255,255,255,0.1); border-radius: 8px; background-color: rgba(255,255,255,0.02);">
  <div class="post-entry-date" style="font-weight: bold; color: #9ca3af; margin-bottom: 8px;">{{ post.date | date: "%B %Y" }}</div>
  <h3 style="margin-top: 0;"><a href="{{ post.url | relative_url }}" style="color: #60a5fa; text-decoration: none;">{{ post.title }}</a></h3>
  <p>{{ post.excerpt | strip_html | truncatewords: 40 }}</p>
  <p style="margin-top: 12px;">
    <a href="{{ post.url | relative_url }}" class="buy-btn" style="color: #ffffff !important; background-color: #2563eb; padding: 8px 16px; border-radius: 6px; text-decoration: none; display: inline-block; font-weight: bold; font-size: 0.9em; box-shadow: 0 2px 4px rgba(0,0,0,0.3);">
      Read Full Article &rarr;
    </a>
  </p>
</div>
{% endfor %}

---

> **Usage Note:** Every time the site is updated, a new Markdown (`.md`) file is added inside `_posts/` with the date, title of the new theory or breakthrough, and detailed text. See `_posts/` in the repository for the exact format.
