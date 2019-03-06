---
layout: gridlay
title: RayoLab - Equipo
excerpt: Miembros - Rayolab @ Universidad de Chile
sitemap: false
permalink: /equipo
---
# Equipo

## Fundadores

<table align="center" style="width:100%">
  <tr>
    <td>Ph.D. Humberto Maturana Romesín</td>
    <td>Ph.D. Francisco Varela García</td>
  </tr>
  
</table>

## Staff

{% assign number_printed = 0 %}
{% for member in site.data.investigadores.miembros %}

{% assign even_odd = number_printed | modulo: 2 %}

{% if even_odd == 0 %}

<div class="row">
{% endif %}

<div class="col-sm-6 clearfix">
  <img src="{{ member.photo }}" class="img-responsive" width="25%" style="float: left" />
  <h4>{{ member.name }}</h4>
  <i>{{ member.info }}<br>email: <{{ member.email }}></i>
  <ul style="overflow: hidden">

  {% if member.number_educ == 1 %}

  <li> {{ member.education1 }} </li>
  {% endif %}

  {% if member.number_educ == 2 %}

  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  {% endif %}

  {% if member.number_educ == 3 %}

  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  {% endif %}

  {% if member.number_educ == 4 %}

  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  <li> {{ member.education4 }} </li>
  {% endif %}

  {% if member.number_educ == 5 %}

  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  <li> {{ member.education4 }} </li>
  <li> {{ member.education5 }} </li>
  {% endif %}

  </ul>
</div>

{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd == 1 %}

</div>
{% endif %}

{% endfor %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if even_odd == 1 %}

</div>
{% endif %}

## Miembros formados

<table align="center" style="width:100%">
  <tr>
    <td>Patricio Ahumada</td>
    <td>Scarlett Delgado</td>
    <td>Isidora Valdevenito</td>
    <td>Cristian González-Cabrera</td>
  </tr>
    <tr>
    <td>Daniel Opazo</td>
    <td>Pedro Fernández-Aburto</td>
    <td>Daviel Severín</td>
    <td>Sebastián Tapia Pino</td>
  </tr>
  <tr>
    <td>Sergio Soto</td>
    <td>Miguel Salinas</td>
    <td>Karina Buldrini</td>
    <td>Cristian Morales</td>
  </tr>
  <tr>
    <td>Juan Salazar</td>
    <td>Bryan Reynaert</td>
    <td>Edgardo Ramírez</td>
    <td>Daniel Smith</td>
  </tr>
  <tr>
    <td>Camila Weiss-Garrido</td>
    <td>Florencia Garrido</td>
    <td>Natalia Madrid</td>
    <td>Daniel Núñez</td>
  </tr>
  <tr>
    <td>Pablo Riveros</td>
    <td>Francisca Toledo</td>
    <td>Amaranta Valdés</td>
    <td>David Rojas</td>
  </tr>
  <tr>
    <td>Claudia Cecchi</td>
    <td>Cristián Villagra</td>
    <td>Javier Díaz</td>
    <td>David Rubilar Rogers</td>
  </tr>
  <tr>
    <td>Felipe Fredes</td>
    <td>Rodrigo Suárez</td>
    <td>Tomás Vega</td>
    <td>Susana Vargas</td>
  </tr>
  <tr>
    <td>Carolina Simon Gutstein</td>
    <td>Nicolás Gravel</td>
    <td>Macarena Faunes</td>
    <td>Jorge Gibbons</td>
  </tr>
  <tr>
    <td>Carlos Salas</td>
    <td>Denisse Carrasco</td>
    <td>Ernesto Durán</td>
    <td>Ricardo Santa María</td>
  </tr>  
  <tr>
    <td>Santiago Martinich</td>
    <td>Cecilia Concha</td>
    <td>Felipe Medina</td>
    <td>Michaela Vergara</td>
  </tr>
  <tr>
    <td>Camila Valenzuela</td>
    <td>Hans Pottstock</td>
    <td>Carlos Martinoya</td>
    <td>Raúl BerrÍos</td>
  </tr>
  <tr>
    <td>José Palma</td>
    <td>Sebastián Tapia</td>
    <td>Rosita Lizana</td>
    <td>Gloria Guiloff</td>
  </tr>
  <tr>
    <td>Mónica Quiroz</td>
    <td>Jorge Golowash</td>
    <td>Ximena Rojas</td>
    <td>Vivian Budnik</td>
  </tr>
  <tr>
    <td>Francisco Aboitiz</td>
    <td>Michel Gho</td>
    <td>Alfredo Kirkwood</td>
    <td>Carmen Cordero</td>
  </tr>
  <tr>
    <td>Rafael Panteón</td>
    <td>Frank Sampson</td>
    <td>John Ewer</td>
    <td>Patricio Huerta</td>
  </tr>
  <tr>
    <td>Pedro Maldonado</td>
    <td>Marilú Aylwin</td>
    <td>Cecilia Babul</td>
    <td>Miguel Concha</td>
  </tr>
  <tr>
    <td>Hernán Díaz</td>
    <td>Carlos Rozas</td>
    <td>Javier Muñoz</td>
    <td>Juan Concha</td>
  </tr>
  <tr>
    <td>Carlos Madrid</td>
    <td>Daniver Morales</td>
    <td>Marcelo Velasco</td>
    <td>Pablo Henny</td>
  </tr>
  <tr>
    <td>Pamela Weber</td>
    <td>Gonzalo Farfán</td>
    <td>Nélida Pohl</td>
    <td>Susana Vargas</td>
  </tr>
  <tr>
    <td>Camilo Libedinsky</td>
    <td>Magdalena Carrasco</td>
    <td>Felipe Medina</td>
    <td>Tomás Ossandón</td>
  </tr>
  <tr>
    <td>Yael Codriansky</td>
    <td>Jaime Martínez</td>
    <td>Cristian Gutierrez</td>
    <td>Carla Alvial</td>
  </tr>
  <tr>
    <td>Oscar Hernández</td>
    <td>Pablo Sabat</td>
    <td>Patricio García</td>
    <td>Adrián Palacios</td>
  </tr>
  <tr>
    <td>Francisco Flores</td>
    <td>Daniela Vera</td>
    <td>Luciana López-Jury</td>
    <td></td>
  </tr>
</table>

## Colaboradores

<table align="center" style="width:100%">
  <tr>
    <td>Harvey Karten (UCSD, USA)</td>
    <td>Shigeru Watanabe (Keio University, Japan)</td>
    <td>Athel Cornish-Bowden (CNRS, France)</td>
    <td>María Luz Cárdenas-Cerda (CNRS, France)</td>
  </tr>
  <tr>
    <td>Jorge Soto Andrade (UCH, Chile)</td>
    <td>Claudio Gutierrez (UCH, Chile)</td>
    <td>Hiroshi Yasuda (Tokio University, Japan)</td>
    <td>Eduardo Vera (UCH, Chile)</td>
  </tr>
  <tr>
    <td>Mark Alan Hershkovitz</td>
    <td>Carolina Villagrán (UCH, Chile)</td>
    <td>Antonio Glaria (UV, Chile)</td>
  </tr>
 
</table>

## Actualizaciones de la web

<a href="mailto:rodrigo.dover@ug.uchile.cl">Rodrigo Dover</a> está a cargo de la actualización y mantención de la web.
