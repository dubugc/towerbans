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
  </div>

  <hr />

  <div style="margin-top: 2rem;">
    <h2 style="color: #f48fb1;">📜 Bannable Offences</h2>
    <ul style="padding-left: 1.2em; line-height: 1.6;">
      <li>Harassment or targeted abuse</li>
      <li>NSFW or pornographic content in public condos</li>
      <li>Gore or shock imagery</li>
      <li>Underage/cub/shotacon/lolicon content (even stylised)</li>
      <li>Evading moderation via alt accounts</li>
      <li>Hosting condos for banned users</li>
      <li>Use of slurs or hate speech</li>
      <li>Persistent griefing or trolling</li>
    </ul>
  </div>

  <div style="margin-top: 2rem;">
    <h2 style="color: #ce93d8;">🚫 Censored Words</h2>
    <p style="font-size: 0.95em; color: #aaa;">Words blocked automatically by our moderation system:</p>
    <div style="background-color: #2a2a2a; padding: 1em; border-radius: 6px; font-size: 0.95em; color: #eee;">
      <code>nigger, faggot, kike, tranny, rape, cp, cub, shota, loli, zoophilia, bestiality</code>
    </div>
  </div>

  <hr style="margin-top: 2.5rem;" />

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
