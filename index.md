---
layout: default
title: TowerBans
---

<div class="container">

  <div style="text-align: center; margin-top: 2rem;">
    <h1>🍔 TowerBans</h1>
    <p style="font-size: 1.2em; color: #bbb;">
      A blog uncovering moderation issues, transparency problems, and broken systems in Tower Unite.
    </p>
  </div>

  <hr />

  <ul style="list-style: none; padding-left: 0;">
    {% for post in site.posts %}
      <li style="margin-bottom: 1.5em;">
        <a href="{{ site.baseurl }}{{ post.url }}" style="font-size: 1.2em; font-weight: 600; color: #90caf9;">
          {{ post.title }}
        </a><br />
        <small style="color: #888;">{{ post.date | date: "%d %B %Y" }}</small>
      </li>
    {% endfor %}
  </ul>

</div>
