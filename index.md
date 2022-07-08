---
layout : default
title: Guías de gobierno para un Chapter.
---

## ¿Es momento de cambio?

Lee la carta de presentación de esta iniciativa aquí : [¿Es momento de cambio?](README.md)

Este repositorio servirá de banco de trabajo para el desarrollo y evolución de guías que la Junta Directiva de un Chapter pueden aplicar en la legislatura que sostienen.

Estos textos no son vinculantes ni se pueden elevar a rango de textos reguladores dado que los únicos textos normativos del Club Venox y todos sus chapters son Los Estatutos y el Reglamento Interno.

Estos textos quedan a disposición de las Juntas Directivas del Chapter como guías y pautas que se tomaron en el pasado y fueron aceptadas por la mayoría de socios del Chapter para gobernar la convivencia del Chapter.

## Espíritu

El espíritu de estas guías es el de proponer procesos de gobierno aplicables a un Chapter de manera que los socios sostengan el poder de decision, fomentando así una mayor sentimiento de pertenencia y la capacidad de influir en las decisiones que se toman.

Este estilo de gobierno precisa de una mayoría de socios activos en el gobierno del Chapter.

El role de la Junta Directiva es la de arbitrar y ejecutar la voluntad de los socios.
Solo en caso de bloqueo la Junta Directiva, y en ultima instancia el Presidente, tendrán poder suficiente para resolver y avanzar en las decisiones necesarias.

## [Las Guías](guias.html)

Esta es la lista de guías desarrolladas por el momento.
Si ves que falta alguna que ayudaría tener para facilitar la convivencia y gobierno del chapter no dudes en proponerselo a la Junta Directiva.

{% assign guias = (site.guias | sort: 'date') %}
{% for guia in guias %}
1. [{{guia.title}}]({{ site.baseurl }}{{ guia.url }}){% endfor %}
