---
title : page
title: Comencemos.
---


Este repositorio servirá de banco de trabajo para el desarrollo y evolución de guías que la Junta Directiva de un Chapter pueden aplicar en la legislatura que sostienen.

Estos textos no son vinculantes ni se pueden elevar a rango de textos reguladores dado que los únicos textos normativos del Club Venox y todos sus chapters son Los Estatutos y el Reglamento Interno.

Estos textos quedan a disposición de las Juntas Directivas del Chapter como guias y pautas que se tomaron en el pasado y fueron aceptadas por la mayoría de socios del Chapter para gobernar la convivencia del Chapter.

## Espíritu
El espíritu de estas guías es la de proponer procesos de gobierno del Chapter de manera que los socios sostengan el poder de decision, fomentando asi en los socios una mayor sentimiento de pertenencia y de influencia en las decisiones relacionadas con el Chapter. 

Este estilo de gobierno precisa de una mayoría de socios involucrada y activa en el gobierno del Chapter. 

El role de la Junta Directiva es la de arbitraje y ejecución de la voluntad de los socios. 
Solo en caso de bloqueo la Junta Directiva, y en ultima instancia el Presidente, tendrán poder suficiente para resolver y avanzar en las decisiones necesarias.

## [Guias](guias.html)
{% assign guias = (site.guias | sort: 'date') | reverse %}
{% for guia in guias %}
1. [{{guia.title}}]({{guia.relative_path}})
{% endfor %}

## Guias
1. [Junta Directiva](JuntaDirectiva.md)
1. [Órganos de Decisión](OrganosDeDecision.md)
1. [Proceso de Admisión](ProcesoDeAdmision.md)
1. [Resolución de conflictos con no socios](ResolucionDeConflictosConNoSocios.md)
1. [Votación Telemática](VotacionTelematica.md)
