---
layout: page
title: Civic housing
description: Architecture
location: Tan Thach commune, Chau Thanh town, Ben Tre province, Vietnam.
date: 2023-01-01
inline: false
related_posts: false
pdf: "2023 Project 01 Civic housing.pdf"
---


<p><b>Year:</b> Nov 2022 - March 2023</p>

{% if page.location %}
<p><b>Location:</b> {{ page.location}}</p>
{% endif %}

<p><b>Architectural designer:</b> My-Hung Nguyen</p>
<p><b>Supervision:</b> Vo Ngoc Truong</p>



<br>
<hr>

{% if page.pdf %}
<h2><a href="{{ page.pdf | prepend: 'assets/pdf/' | relative_url}}" target="_blank" rel="noopener noreferrer" class="float-right"><i class="fas fa-file-pdf"></i></a></h2>
<iframe src="/assets/pdf/{{page.pdf}}#view=fitH" width="100%" height="900" frameborder="no" border="0" marginwidth="0" marginheight="0"></iframe>
{% endif %}