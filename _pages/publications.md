---
layout: page
permalink: /publications/
title: publications
description: This page contains the list of my publications and preprints.
nav: true
nav_order: 2
---

<!-- _pages/publications.md -->
<div class="publications">

<h2>Scientific papers</h2>
{% bibliography --query @*[doc_type!=these]* %}

<h2>Theses</h2>
{% bibliography --query @*[doc_type=these]* %}

</div>





