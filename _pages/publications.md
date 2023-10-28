---
layout: page
permalink: /publications/
title: Research
description: 
nav: true
nav_order: 1
---
<!-- _pages/publications.md -->
<div class="publications">

<h1 style="text-align: left;">Publications</h1>
{% bibliography --query @publication %}

<h1 style="text-align: left;">Projects</h1>
{% bibliography --query @project %}

</div>
