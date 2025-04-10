---
layout: default
title: Artwork
permalink: /artwork/
---

<h2 class="text-center">Proceso de Animación</h2>

<div class="gallery-artwork">
  {% for artwork in site.data.artwork %}
    <div class="artwork-card">
      <a href="{{ artwork.permalink }}" class="artwork-link">
      <img 
        src="/assets/img/artwork/{{ artwork.image }}" 
        alt="{{ artwork.title }}"
        loading="lazy"
      >
      
      <div class="artwork-info">
        <h3>{{ artwork.title }}</h3>
        <p>{{ artwork.description }}</p>
        <span class="artwork-date">{{ artwork.date }}</span>
      </div>
      </a>
    </div>
  {% endfor %}
</div>