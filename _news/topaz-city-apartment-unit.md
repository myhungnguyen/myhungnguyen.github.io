---
layout: page
title: Topaz City Apartment unit
description: Interior design
location: 39 Đ. Cao Lo Street, Ward No.4, District 8, Ho Chi Minh City, Vietnam.
date: 2023-03-01 07:59:00-0400
inline: false
related_posts: false
pdf: "2023 03 folio Topaz city apartment interior design.pdf"
---


{% if page.date %}
<p><b>Year:</b> {{ page.date | date: "%B, %Y" }}</p>
{% endif %}

{% if page.location %}
<p><b>Location:</b> {{ page.location}}</p>
{% endif %}

<p><b>Lead architect:</b> Vo Ngoc Truong</p>
<p><b>Associate:</b> My-Hung Nguyen</p>

<br>
<hr>
<h2>{% if page.pdf %}<a href="{{ page.pdf | prepend: 'assets/pdf/' | relative_url}}" target="_blank" rel="noopener noreferrer" class="float-right"><i class="fas fa-file-pdf"></i></a>{% endif %}</h2>

<iframe src="/assets/pdf/2023 03 folio Topaz city apartment interior design.pdf#view=fitH" width="100%" height="900" frameborder="no" border="0" marginwidth="0" marginheight="0"></iframe>

<!-- <iframe allowfullscreen="allowfullscreen" scrolling="no" class="fp-iframe" style="border: 1px solid lightgray; width: 100%; height: 400px;" src="https://heyzine.com/flip-book/e8c5cece62.html"></iframe> -->