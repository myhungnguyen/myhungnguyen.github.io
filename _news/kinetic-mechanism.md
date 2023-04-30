---
layout: page
title: Kinetic Mechanism
description: Technology, 3D Fabrication
location: Melbourne, Australia.
date: 2021-03-01
inline: false
related_posts: false
pdf: "Kinetic Mechanism.pdf"
---


{% if page.date %}
<p><b>Year:</b> {{ page.date | date: "%Y" }}</p>
{% endif %}



{% if page.location %}
<p><b>Location:</b> {{ page.location}}</p>
{% endif %}

<p><b>Maker:</b> My-Hung Nguyen</p>
<br>
<p><b>Abstract</b></p>
<p>For this mechanism, the robotic movement which is driven from wind energy or electricity performs in an artistic sense as a living creature walking on a surface.</p>
<p>This prototype is referred for further implications on automatic transportation and robotics.</p>

<br>
<hr>

<figure>
  <video width="100%" height=auto controls>
    <source src="/assets/video/3D_0609_2032.mp4" type="video/mp4">
    <source src="movie.ogg" type="video/ogg">
    Your browser does not support the video tag.
  </video>
  <figcaption style="text-align: center;">Electronics is embedded into the mechanism for simulating the motions.</figcaption>
</figure>
<br>
<figure>
  <div class="sketchfab-embed-wrapper"> 
    <iframe title="Kintetic Mechanism" frameborder="0" allowfullscreen mozallowfullscreen="true" webkitallowfullscreen="true" allow="autoplay; fullscreen; xr-spatial-tracking" xr-spatial-tracking execution-while-out-of-viewport execution-while-not-rendered web-share width="55%" height="250" src="https://sketchfab.com/models/96821adc985243ce9377a13492c7fd59/embed"> </iframe> 
    <img align="right" src="/assets/img/rendering_2021-may-27_05-34-56am-000_customizedview11288881651_png.png" alt="a prototype image" width="42%" height=250>
    <p style="font-size: 13px; font-weight: normal; margin: 5px; color: #4A4A4A;"> <a href="https://sketchfab.com/3d-models/kintetic-mechanism-96821adc985243ce9377a13492c7fd59?utm_medium=embed&utm_campaign=share-popup&utm_content=96821adc985243ce9377a13492c7fd59" target="_blank" rel="nofollow" style="font-weight: bold; color: #1CAAD9;"> Kintetic Mechanism </a> by <a href="https://sketchfab.com/hungnguyen-mh?utm_medium=embed&utm_campaign=share-popup&utm_content=96821adc985243ce9377a13492c7fd59" target="_blank" rel="nofollow" style="font-weight: bold; color: #1CAAD9;"> hungnguyen-s3821941 </a> on <a href="https://sketchfab.com?utm_medium=embed&utm_campaign=share-popup&utm_content=96821adc985243ce9377a13492c7fd59" target="_blank" rel="nofollow" style="font-weight: bold; color: #1CAAD9;">Sketchfab</a></p>
  </div>
  <figcaption style="text-align: center;">Interactive display on Sketchfab</figcaption>
</figure>


<h2>{% if page.pdf %}<a href="{{ page.pdf | prepend: 'assets/pdf/' | relative_url}}" target="_blank" rel="noopener noreferrer" class="float-right"><i class="fas fa-file-pdf"></i></a>{% endif %}</h2>
<iframe src="/assets/pdf/Kinetic Mechanism.pdf#view=fitH" width="100%" height="900" frameborder="no" border="0" marginwidth="0" marginheight="0"></iframe>
