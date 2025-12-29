---
layout: single
title: "Workshops"
permalink: /workshops/
---

<section class="section-container" id="workshops">
  <h2 class="section-title">Workshop Videos</h2>
  <div style="max-width: 1200px; margin: 0 auto;">
    <div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(320px, 1fr)); gap: 30px;">
      {% assign vids = site.workshops | sort: 'date' | reverse %}
      {% for w in vids %}
      <div style="background: rgba(255, 255, 255, 0.08); backdrop-filter: blur(10px); border: 1px solid rgba(255, 140, 0, 0.3); border-radius: 12px; overflow: hidden; transition: all 0.4s ease;">
        {% if w.video_id %}
        <iframe width="100%" height="250" src="https://www.youtube.com/embed/{{ w.video_id }}" title="{{ w.title }}" style="border: none;" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" loading="lazy" allowfullscreen></iframe>
        {% else %}
        <div style="position: relative; width: 100%; padding-bottom: 56.25%; background: linear-gradient(135deg, #0a1628, #1a2845); display: flex; align-items: center; justify-content: center;">
          <a href="{{ w.external_url }}" target="_blank" style="position: absolute; width: 100%; height: 100%; display: flex; align-items: center; justify-content: center; text-decoration: none;">
            <i class="fas fa-graduation-cap" style="font-size: 4rem; color: var(--accent-orange); opacity: 0.8;"></i>
          </a>
        </div>
        {% endif %}
        <div style="padding: 25px;">
          <h3 style="color: var(--white); margin-bottom: 12px; font-size: 1.2rem;">{{ w.title }}</h3>
          {% if w.description %}
          <p style="color: rgba(255, 255, 255, 0.8); margin-bottom: 20px; font-size: 0.95rem;">{{ w.description }}</p>
          {% endif %}
          <div style="display: flex; gap: 8px; margin-bottom: 15px;">
            {% if w.topics %}
            {% for t in w.topics %}
            <span style="background: rgba(255, 140, 0, 0.3); color: var(--accent-orange); padding: 4px 10px; border-radius: 20px; font-size: 0.8rem;">{{ t }}</span>
            {% endfor %}
            {% endif %}
          </div>
          {% if w.external_url %}
          <a href="{{ w.external_url }}" target="_blank" style="display: inline-block; color: var(--accent-orange); text-decoration: none; font-weight: 600;">View <i class="fas fa-external-link-alt" style="margin-left: 8px;"></i></a>
          {% endif %}
        </div>
      </div>
      {% endfor %}
    </div>
  </div>
</section>
