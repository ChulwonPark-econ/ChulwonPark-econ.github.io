---
layout: page
permalink: /publications/
title: publications
description: Published research and working papers.
nav: true
nav_order: 2
---

<!-- _pages/publications.md -->

<!-- Bibsearch Feature -->

{% include bib_search.liquid %}

<div class="publications">

<h2>Published</h2>

{% bibliography --group_by year --group_order descending --query @*[journal!=Working Paper] %}

<h2>Working Papers</h2>

{% bibliography --group_by none --query @*[journal=Working Paper] %}

</div>
