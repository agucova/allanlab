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
    <td>Nikolaos Iliopoulos, Spring 2016</td>
    <td>Bert Visscher, Fall 2017</td>
    <td>Vishnu Saj, Spring 2017</td>
  </tr>
  <tr>
    <td>Vitaly Fedoseev, all of 2016</td>
    <td>Ahmad Jamalzada, Fall 2017</td>
    <td>Joey Braspenning, Spring 2017</td>
  </tr>
  <tr>
    <td>Ramakrishna Aluru, Summer 2018</td>
    <td>Tjerk Benschop, Summer 2017</td>
    <td>Margot Leemker, Spring 2017</td>
  </tr>
  <tr>
    <td></td>
    <td>Oliver Ostojic, Spring 2016</td>
    <td>Sietske Lensen, Spring 2017</td>
  </tr>
  <tr>
    <td></td>
    <td>Farshaad Hoeseni, Fall 2015</td>
    <td>Alexander Vanstone, Spring 2016</td>
  </tr>
  <tr>
    <td></td>
    <td></td>
    <td>Tjerk Benschop, Spring 2016</td>
  </tr>
  <tr>
    <td></td>
    <td></td>
    <td>Arjo Andringa, Spring 2016</td>
  </tr>
  <tr>
    <td></td>
    <td></td>
    <td>Daniëlle van Klink, Spring 2016</td>
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

## Soporte Administrativo

<a href="mailto:Rijsewijk@Physics.LeidenUniv.nl">Ellie van Rijsewijk</a> is helping us (and other groups) with administration.
