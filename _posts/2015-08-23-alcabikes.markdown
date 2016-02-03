---
layout: post
title: "Alcabikes - Encuentra un Parking de Bicicletas en Alcalá"
date: 2015-08-23
categories:
---

![Alcabikes](/onclick/post_images/2015-08-24-alcabikes/alcabikes.png)

Antes de empezar a trabajar en [Planificando](http://planificando.org) participé en un pequeño curso gratuito que organizaron en la [Universidad de Alcalá ](http://www.uah.es/), en el que se impartieron algunas tecnologías web. En una de las jornadas del curso se recomendaba trastear con las tecnologías del día y decidí hacer algo muy simple, pero que pudiese ser de provecho; y quedó así.

A partir de un geojson -el ayuntamiento de Alcalá ofrece un pdf con la ubicación de los aparcamientos, que traduje a mano a json- que se carga en el mapa se pueden visualizar los aparcamientos, y gracias a HTML5, se puede localizar la posición del dispositivo y se ofrece un aparcamiento cercano.

Tecnologías utilizadas:

- [GeoJson](http://geojson.org) - estándar Json para su uso en mapas.
- [Leafleft](http://leafletjs.com) - para embeber los mapas y los marcadores.
- [Turf](http://turfjs.org) - para calcular el parking más cercano.
- [Bootstrap](http://getbootstrap.com) - web responsive & tema no oficial.

Podéis acceder a la aplicación en [ctacon.me/alcabikes](http://carlosjtacon.com/alcabikes/) (Desktop & Mobile).