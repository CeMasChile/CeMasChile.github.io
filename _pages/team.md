---
layout: page
permalink: /team
title: "Nuestro Equipo"
description: "Somos un variado equipo compuesto por estudiantes, académic@s y profesor@s principalmente de Ingeniería (por el momento) entregad@s a un trabajo impecable, responsable y ético al servicio de la comunidad"
---

{% for area in site.data.teams.team %}
<div class="bg-white py-5">
    <div class="container py-5">
        <div class="row text-center">
            <div class="col md 12">
                <h2 class="font-weight-light">{{ area.name }}</h2>
            </div>
        </div>
    </div>
</div>

<div class="bg-white py-5">
      <div class="container py-5">   
          <div class="row text-center">
          <!-- Team item-->
            {% for member in area.members %}
              <div class="col-xl-3 col-sm-6 mb-5">
                  <div class="bg-white rounded shadow-sm py-5 px-4">
                      <img src="{{ member.item.photo }}" alt="" width="100" class="img-fluid rounded-circle mb-3 img-thumbnail shadow-sm">
                      <h5 class="mb-0">{{ member.item.name }}</h5>
                      <span class="small text-uppercase text-muted">{{member.item.job}}</span>
                  </div>
              </div> 
          <!-- End-->     
          {% endfor %}
          </div>
      </div>
</div>
{% endfor %}

{% for area in site.data.teams %}




{% endfor %}
