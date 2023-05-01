---
layout: page
title: Mood Tool
description: Technology, Interaction Design
location: Melbourne, Australia.
date: 2020-03-01
inline: false
related_posts: false
pdf: "2020 Mood Tool.pdf"
video: "2020 Technology studio - compressed.mp4"
---


{% if page.date %}
<p><b>Year:</b> {{ page.date | date: "%Y" }}</p>
{% endif %}



{% if page.location %}
<p><b>Location:</b> {{ page.location}}</p>
{% endif %}

<p><b>Team:</b> Siyu Yao, Shrusti Basavaraj Malimath, Thanchanok Klabson, My-Hung Nguyen</p>
<br>
<p><b>Abstract</b></p>
<p>Social media addiction has been a topic of discussion for many years now. The consequences of overuse and over-reliance on social media are still being studied and understood but so far the consensus is that too much social media can have a negative impact on your mood and wider mental health.</p>
<p>Mood tool is designed to relieve the reliance on social media by sending push notifications to a user if too much time is spent on it. Mood tool also takes inspiration from music as a form of therapy. It uses music to help a wearers distract themselves from social media by offering musical selections which the user can select according to how they feel. Music helps to release emotions such as stress, anxiety, sadness, and anger, while reinforcing positive emotions such as joy and contentedness.</p>

<br>
<hr>

<figure>
    <div id="carouselExampleIndicators" class="carousel slide" data-ride="carousel">
    <ol class="carousel-indicators">
        <li data-target="#carouselExampleIndicators" data-slide-to="0" class="active"></li>
        <li data-target="#carouselExampleIndicators" data-slide-to="1"></li>
        <li data-target="#carouselExampleIndicators" data-slide-to="2"></li>
        <li data-target="#carouselExampleIndicators" data-slide-to="3"></li>
        <li data-target="#carouselExampleIndicators" data-slide-to="4"></li>
    </ol>
    <div class="carousel-inner">
        <div class="carousel-item active">
        <img src="/assets/img/1-heroshot.jpg" class="d-block w-100" alt="...">
        </div>
        <div class="carousel-item">
        <img src="/assets/img/2-MOOD TOOLfinal-17 copy.jpg" class="d-block w-100" alt="...">
        </div>
        <div class="carousel-item">
        <img src="/assets/img/3-MOOD TOOLfinal-18 copy.jpg" class="d-block w-100" alt="...">
        </div>
        <div class="carousel-item">
        <img src="/assets/img/4-MOOD TOOLfinal-19 copy.jpg" class="d-block w-100" alt="...">
        </div>
        <div class="carousel-item">
        <img src="/assets/img/5-moodtool concept-01.jpg" class="d-block w-100" alt="...">
        </div>
    </div>
    <button class="carousel-control-prev" type="button" data-target="#carouselExampleIndicators" data-slide="prev">
        <span class="carousel-control-prev-icon" aria-hidden="true"></span>
        <span class="sr-only">Previous</span>
    </button>
    <button class="carousel-control-next" type="button" data-target="#carouselExampleIndicators" data-slide="next">
        <span class="carousel-control-next-icon" aria-hidden="true"></span>
        <span class="sr-only">Next</span>
    </button>
    </div>
    <figcaption style="text-align: center;"><b>Mood Tool</b></figcaption>
    <figcaption style="text-align: center;">A calm intervention for social media bingers</figcaption>
</figure>

<br>

<figure>
  <video width="100%" height=auto controls>
    {% if page.video %}
    <source src="/assets/video/{{page.video}}" type="video/mp4">
    {% endif %}
  </video>
  <figcaption style="text-align: center;"><b>Technological user experience demonstration</b></figcaption>
  <figcaption style="text-align: center;">Programmed & video edited: Hung Nguyen</figcaption>
</figure>
<br>

{% if page.pdf %}
<h2><a href="{{ page.pdf | prepend: 'assets/pdf/' | relative_url}}" target="_blank" rel="noopener noreferrer" class="float-right"><i class="fas fa-file-pdf"></i></a></h2>
<iframe src="/assets/pdf/{{page.pdf}}#view=fitH" width="100%" height="900" frameborder="no" border="0" marginwidth="0" marginheight="0"></iframe>
{% endif %}