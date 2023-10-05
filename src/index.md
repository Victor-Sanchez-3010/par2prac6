---
layout: base.njk
title: Victor Sanchez
---

# {{ title }}

### El mas cabron de los cabroncitos

[Acerca]({{ '/acerca' | url }})

## Blogs

### Videojuegos

{% for juego in collections.juegos %}

- [{{juego.data.title}}]({{ juego.url | url }})

{% endfor %}

### Series

{% for serie in collections.series %}

- [{{serie.data.title}}]({{ serie.url | url }})

{% endfor %}

### Peliculas

{% for pelicula in collections.peliculas %}

- [{{pelicula.data.title}}]({{ pelicula.url | url }})

{% endfor %}
