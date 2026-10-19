---
layout: page
permalink: /publications/
title: publications
description: Preprints, Journal articles, book chapters, and books.
nav: true
nav_order: 2
---

<style>
  .publications h2.bibliography {
    color: var(--global-text-color) !important;
    opacity: 0.75;
    font-weight: 500;
  }
</style>

<!-- _pages/publications.md -->

<!-- Bibsearch Feature -->

{% include bib_search.liquid %}

<div class="publications">

{% bibliography %}

</div>
