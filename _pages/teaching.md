---
layout: page
permalink: /teaching/
title: teaching
description: Course materials, schedules, and resources for classes taught.
nav: true
nav_order: 6
calendar: true
---

Mi labor docente tiende un puente entre la física fundamental de la mecánica de medios continuos y las herramientas computacionales avanzadas. Los cursos se centran en la formulación matemática de la dinámica de fluidos (Navier-Stokes) y en la aplicación de la dinámica de fluidos computacional (CFD) y de modelos de mesoescala para resolver problemas aerodinámicos y atmosféricos reales en el ámbito de la energía eólica.

{% include figure.liquid 
   path="assets/img/lineasinves.png" 
   class="img-fluid rounded z-depth-1" 
   zoomable=true 
   alt="Líneas de investigación desarrolladas en el ICAyCC-UNAM"
   caption="Figura 1: Líneas de investigación desarrolladas en el ICAyCC-UNAM." 
%}

{% include courses.liquid %}

<div class="row justify-content-center">
  <div class="col-sm-10 mt-3">
    <video class="img-fluid rounded z-depth-1" autoplay loop muted playsinline width="100%">
      <source src="{{ '/assets/video/Turbina1' | relative_url }}" type="video/mp4">
    </video>
    <div class="caption text-center mt-2">
      Figura 2: Evolución temporal de la estela mediante dinámica de fluidos computacional.
    </div>
  </div>
</div>

{% include figure.liquid 
   path="assets/img/analytical_alan.gif" 
   class="img-fluid rounded z-depth-1" 
   zoomable=false 
   alt="Animación de dinámica de fluidos"
   caption="Figura 3: Simulación numérica de la capa límite atmosférica interactuando con el rotor de un aerogenerador." 
%}

{% include figure.liquid 
   path="assets/img/vtkWindFarmHorizontal.gif" 
   class="img-fluid rounded z-depth-1" 
   zoomable=false 
   alt="Simulación CFD de capa límite atmosférica"
   caption="Figura 4: Simulación numérica mediante CFD del perfil de velocidades del viento y turbulencia en terrenos complejos." 
%}


{% include figure.liquid 
   path="assets/img/Natconv0.png" 
   class="img-fluid rounded z-depth-1" 
   zoomable=true 
   alt="Simulación CFD de capa límite atmosférica"
   caption="Figura 5: Convección Natural Seca." 
%}
