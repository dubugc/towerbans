---
layout: default
title: TowerBans
---

<div style="text-align: center;">
  <h1>🧱 TowerBans</h1>
  <p style="font-size: 1.2em;">A blog uncovering moderation issues, transparency problems, and broken systems in Tower Unite.</p>
</div>

<hr>

<ul style="list-style: none; padding-left: 0;">
  {% for post in site.posts %}
    <li style="margin-bottom: 1em;">
      <a href="{{ site.baseurl }}{{ post.url }}" style="font-size: 1.1em; font-weight: bold; color: #0066cc;">
        {{ post.title }}
      </a><br>
      <small style="color: #999;">{{ post.date | date: "%d %B %Y" }}</small>
    </li>
  {% endfor %}
</ul>
