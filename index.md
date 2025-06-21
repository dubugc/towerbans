---
layout: default
title: TowerBans
---

<div class="container">

  <div style="text-align: center; margin-top: 2rem;">
    <h1>🍔 TowerBans 🍔</h1>
    <p style="font-size: 1.2em; color: #bbb;">
      Transparency and fairness are paramount in our community.
    </p>

    <!-- Visible rule links below header -->
    <div style="margin-top: 1rem;">
      <a href="{{ site.baseurl }}/rules/" style="margin-right: 1.5em; font-weight: bold; color: #f48fb1;">
        🔗 Bannable Rules
      </a>
      <a href="{{ site.baseurl }}/censored-words/" style="font-weight: bold; color: #ce93d8;">
        🔗 Censored Words
      </a>
      </a>
      <a href="{{ site.baseurl }}/banned-players/" style="font-weight: bold; color: #ce93d8;">
        🔗 Banned Players
      </a>
    </div>
  </div>

  <hr />

  <h2 style="margin-top: 2rem; color: #90caf9;">📚 Blog Archive</h2>

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
