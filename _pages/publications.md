---
layout: page
permalink: /publications/
title: Publications
description: Publications in reversed chronological order.
nav: true
nav_order: 2
---

<!-- _pages/publications.md -->

<div class="wordwrap">You can also find my articles on <a href="https://scholar.google.com/citations?user=vqsl1YYAAAAJ&hl=en&oi=ao">my Google Scholar profile</a>.</div>

<!-- {% include bib_search.liquid %} -->

<div class="publications">

{% bibliography --max_authors 10 %}

<script>
  document.addEventListener('DOMContentLoaded', function () {
    document.querySelectorAll('.publications').forEach((el) => {
      el.innerHTML = el.innerHTML.replace(/Yule Wang/g, '<strong>Yule Wang</strong>');
    });
  });
</script>
