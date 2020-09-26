---
layout: gridlay
title: RayoLab - Equipo
excerpt: Miembros - Rayolab @ Universidad de Chile
sitemap: false
permalink: /equipo
---
# Equipo

## Fundador

<table align="center" style="width:100%">
  <tr>
    <td>Ph.D. Humberto Maturana Romesín</td>
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
<td>Adrián Palacios</td>
<td>Alexander Vargas</td>
<td>Alexandre Jardim-Pimenta</td>
<td>Alfonso Deichler</td>
</tr>
 <tr>
<td>Alfredo Kirkwood</td>
<td>Amaranta Valdés</td>
<td>Andrea Tenreiro</td>
<td>Antonio Glaria</td>
</tr>
 <tr>
<td>Bernardita Mendez</td>
<td>Bryan Reynaert</td>
<td>Camila Berríos</td>
<td>Camila Valenzuela</td>
</tr>
 <tr>
<td>Camila Weiss-Garrido</td>
<td>Camilo Libedinsky</td>
<td>Carla Alvial</td>
<td>Carlos Madrid</td>
</tr>
 <tr>
<td>Carlos Martinoya</td>
<td>Carlos Maureira</td>
<td>Carlos Rozas</td>
<td>Carlos Salas</td>
</tr>
 <tr>
<td>Carmen Cordero</td>
<td>Carolina Norambuena</td>
<td>Carolina Simon Gutstein</td>
<td>Cecilia Babul</td>
</tr>
 <tr>
<td>Cecilia Concha</td>
<td>Claudia Cecchi</td>
<td>Claudio Tapia</td>
<td>Cristian González-Cabrera</td>
</tr>
 <tr>
<td>Cristian Gutierrez</td>
<td>Cristian Morales</td>
<td>Cristián Villagra</td>
<td>Cristina Magro</td>
</tr>
 <tr>
<td>Daniel Núñez</td>
<td>Daniel Opazo</td>
<td>Daniel Smith</td>
<td>Daniela Flores</td>
</tr>
 <tr>
<td>Daniela Vera</td>
<td>Daniver Morales</td>
<td>David Rubilar Rogers</td>
<td>Daviel Severín</td>
</tr>
 <tr>
<td>Denisse Carrasco</td>
<td>Edgardo Ramírez</td>
<td>Eduardo Cabezón</td>
<td>Elisa Sentis</td>
</tr>
 <tr>
<td>Elizabeth Tapia</td>
<td>Ernesto Durán</td>
<td>Felipe Fredes</td>
<td>Felipe Medina</td>
</tr>
 <tr>
<td>Fernando Navea</td>
<td>Florencia Garrido</td>
<td>Francisca Toledo</td>
<td>Francisco Aboitiz</td>
</tr>
 <tr>
<td>Francisco Flores</td>
<td>Francisco Varela</td>
<td>Frank Sampson</td>
<td>Gloria Guiloff</td>
</tr>
 <tr>
<td>Gonzalo Farfán</td>
<td>Gonzalo Marín</td>
<td>Hans Pottstock</td>
<td>Hernán Díaz</td>
</tr>
 <tr>
<td>Humberto Maturana</td>
<td>Ignacio Fuenzalida</td>
<td>Ignacio Perales</td>
<td>Isidora Valdebenito</td>
</tr>
 <tr>
<td>Jaime Martínez</td>
<td>Javier Díaz</td>
<td>Javier Mañalich</td>
<td>Javier Muñoz</td>
</tr>
 <tr>
<td>John Ewer</td>
<td>Jorge Gibbons</td>
<td>Jorge Golowash</td>
<td>Jorge Mpodozis</td>
</tr>
 <tr>
<td>José Antonio Barros</td>
<td>José María Hurtado</td>
<td>José Palma</td>
<td>José Pardo Lemus</td>
</tr>
 <tr>
<td>Juan Capela</td>
<td>Juan Carlos Letelier</td>
<td>Juan Concha</td>
<td>Juan Salazar</td>
</tr>
 <tr>
<td>Karina Buldrini</td>
<td>Leonardo Bich</td>
<td>Loreta Bernucci</td>
<td>Luciana López-Jury</td>
</tr>
 <tr>
<td>Luis Aguilar</td>
<td>Luis Vega</td>
<td>Macarena Faunes</td>
<td>Macarena Ruiz</td>
</tr>
 <tr>
<td>Magdalena Carrasco</td>
<td>Magdalena Sanhueza</td>
<td>Marcelo Velasco</td>
<td>Maricel Quispe</td>
</tr>
 <tr>
<td>Marilú Aylwin</td>
<td>Máximo Fernández</td>
<td>Michaela Vergara</td>
<td>Michel Gho</td>
</tr>
 <tr>
<td>Miguel Concha</td>
<td>Miguel Salinas</td>
<td>Mónica Quiroz</td>
<td>Nancy Zamorano</td>
</tr>
 <tr>
<td>Natalia Madrid</td>
<td>Natalia Márquez</td>
<td>Nélida Pohl</td>
<td>Nelson Vaz</td>
</tr>
 <tr>
<td>Nicolás Gravel</td>
<td>Nicolas Piwonka</td>
<td>Oscar Hernández</td>
<td>Pablo Henny</td>
</tr>
 <tr>
<td>Pablo Riveros</td>
<td>Pablo Sabat</td>
<td>Pamela Weber</td>
<td>Patricio Ahumada</td>
</tr>
 <tr>
<td>Patricio García</td>
<td>Patricio Huerta</td>
<td>Pedro Fernández-Aburto</td>
<td>Pedro Maldonado</td>
</tr>
 <tr>
<td>Rafael Panteón</td>
<td>Raúl Berríos</td>
<td>Ricardo Santa María</td>
<td>Rodrigo Dover</td>
</tr>
 <tr>
<td>Rodrigo Guzmán</td>
<td>Rodrigo Suárez</td>
<td>Ronald Jonas</td>
<td>Rony Silvestre</td>
</tr>
 <tr>
<td>Rosana Reyes</td>
<td>Rosita Lizana</td>
<td>Santiago Martinich</td>
<td>Sara Fernández</td>
</tr>
 <tr>
<td>Scarlett Delgado</td>
<td>Sebastián Jiménez</td>
<td>Sebastián Tapia</td>
<td>Sergio Soto</td>
</tr>
 <tr>
<td>Sima Nisis de Rezepka</td>
<td>Solano Henríquez</td>
<td>Susana Vargas</td>
<td>Tomás Ossandón</td>
</tr>
 <tr>
<td>Tomas Salas</td>
<td>Tomás Vega</td>
<td>Ulises Pereira</td>
<td>Verónica Palma</td>
</tr>
 <tr>
<td>Vicente Muñoz</td>
<td>Vivian Budnik</td>
<td>Ximena Rojas</td>
<td>Yael Codriansky</td>
</tr>
</table>

## Colaboradores

<table align="center" style="width:100%">
  <tr>
    <td>Harvey Karten (UCSD, USA)</td>
    <td>Shigeru Watanabe (Keio University, Japan)</td>
    <td>Athel Cornish-Bowden (CNRS, France)</td>
    <td>María Luz Cárdenas-Cerda
 (CNRS, France)</td>
  </tr>
  <tr>
    <td>Jorge Soto Andrade (UCH, Chile)</td>
    <td>Claudio Gutierrez (UCH, Chile)</td>
    <td>Hiroshi Yasuda (Tokio University, Japan)</td>
    <td>Eduardo Vera (UCH, Chile)</td>
  </tr>
  <tr>
    <td>Mark Alan Hershkovitz
</td>
    <td>Carolina Villagrán (UCH, Chile)</td>
    <td>Antonio Glaria (UV, Chile)</td>
  </tr>
 
</table>

## Actualizaciones de la web

<a href="mailto:rodrigo.dover@ug.uchile.cl">Rodrigo Dover</a> está a cargo de la actualización y mantención de la web.