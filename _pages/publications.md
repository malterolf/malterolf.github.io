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
  .publications .abbr .badge {
    font-size: 0.85rem;
    padding: 0.5em 0.4em;
  }
</style>

<!-- _pages/publications.md -->

<!-- Bibsearch Feature -->

{% include bib_search.liquid %}

<div class="publications">

<h2 class="bibliography">preprints</h2>
{% bibliography --query @*[keywords=preprint] --group_by none %}

{% bibliography --query @*[keywords!=preprint] %}

</div>
