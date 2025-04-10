---
layout: default
title: Personajes
permalink: /personajes/
---

<h2>Mis Personajes</h2>

<div class="personajes">
  {% for personaje in site.data.personajes %}
    <div class="personaje-card">
      <img src="{{ personaje.imagen }}" alt="{{ personaje.nombre }}">
      <h3>{{ personaje.nombre }}</h3>
      <p>{{ personaje.descripcion }}</p>
    </div>
  {% endfor %}
</div>