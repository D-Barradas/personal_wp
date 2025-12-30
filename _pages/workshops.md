---
layout: single
title: "Workshops"
permalink: /workshops/
---

<section class="section-container" id="workshops">
  <h2 class="section-title">Workshop Videos</h2>

  <!-- Featured playlist embeds the entire YouTube list so all videos are available without manual copies -->
  <div style="max-width: 1200px; margin: 0 auto 50px auto; display: grid; grid-template-columns: repeat(auto-fit, minmax(360px, 1fr)); gap: 30px; align-items: stretch;">
    <div style="background: rgba(255, 255, 255, 0.08); border: 1px solid rgba(255, 140, 0, 0.35); border-radius: 14px; overflow: hidden; box-shadow: 0 15px 40px rgba(0,0,0,0.25);">
      <div style="position: relative; padding-bottom: 56.25%; height: 0;">
        <iframe src="https://www.youtube.com/embed/videoseries?list=PLysMdZ_IbOBw5xJCciY_ONGsTfGTPHzDd" title="Workshop Playlist" loading="lazy" style="position:absolute; top:0; left:0; width:100%; height:100%; border:0;" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
      </div>
      <div style="padding: 24px;">
        <p style="color: rgba(255,255,255,0.85); margin: 0 0 10px 0; font-weight: 600; letter-spacing: 0.3px;">Full Playlist</p>
        <h3 style="color: var(--white); margin: 0 0 12px 0; font-size: 1.3rem;">Hands-on Data Science & ML Workshops</h3>
        <p style="color: rgba(255,255,255,0.75); margin: 0;">Browse every session in one place. Use the playlist menu in the player to jump to any workshop.</p>
      </div>
    </div>

    <div style="background: rgba(255, 255, 255, 0.06); border: 1px solid rgba(255, 140, 0, 0.2); border-radius: 14px; padding: 28px; display: grid; gap: 14px; align-content: start;">
      <h3 style="color: var(--white); margin: 0; font-size: 1.2rem;">Quick Links</h3>
      <a href="https://www.youtube.com/playlist?list=PLysMdZ_IbOBw5xJCciY_ONGsTfGTPHzDd" target="_blank" style="color: var(--accent-orange); text-decoration: none; font-weight: 600;">Open playlist on YouTube →</a>
      <p style="color: rgba(255,255,255,0.8); margin: 0;">Tip: click the playlist icon (≡) in the player to select a specific video.</p>
    </div>
  </div>

  <!-- Curated list from site.workshops collection still rendered below -->
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
          <div style="display: flex; gap: 8px; margin-bottom: 15px; flex-wrap: wrap;">
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
