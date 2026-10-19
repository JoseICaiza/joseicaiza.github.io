---
layout: page
permalink: /publications/
title: publications
description: publications by category in reverse chronological order.
nav: true
nav_order: 2
---

<!-- _pages/publications.md -->

<!-- Bibsearch Feature -->

{% include bib_search.liquid %}

<div class="publications">

<h2 class="bibliography">journals</h2>
{% bibliography --group_by none --query @*[category=journal]* %}

<h2 class="bibliography">conferences</h2>
{% bibliography --group_by none --query @*[category=conference]* %}

<h2 class="bibliography">under review &amp; working papers</h2>
{% bibliography --group_by none --query @*[category=review]* %}

</div>
