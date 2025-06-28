---
layout: default
title: TowerBans
---

<div class="container">

  <div style="text-align: center; margin-top: 2rem;">
    <h1>🍔 TowerBans 🍔</h1>

<div class="rule-links">
  <a href="{{ site.baseurl }}/rules/">Bannable Rules</a>
  <a href="{{ site.baseurl }}/censored-words/">Censored Words</a>
  <a href="{{ site.baseurl }}/banned-players/">Banned Players</a>
</div>

    <p style="font-size: 1.2em; color: #bbb;">
      Transparency and fairness are paramount in our community.
    </p>

  <hr />

  <h2 style="margin-top: 2rem; color: #90caf9;">📚 Archive</h2>

<div class="blog-list">
  {% for post in site.posts %}
    <div class="blog-entry">
      <time class="blog-date" datetime="{{ post.date | date_to_xmlschema }}">
        {{ post.date | date: "%d/%m/%Y" }}
      </time>
      <a href="{{ site.baseurl }}{{ post.url }}" class="blog-title">
        {{ post.title }}
      </a>
    </div>
  {% endfor %}
</div>


</div>
