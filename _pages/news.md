---
layout: single
title: News
collection: news
header:
  overlay_image: /assets/images/ath3.jpg
permalink : /news/
classes: wide
entries_layout: grid
---

{% comment %}
News post filenames start with their date (e.g. _news/2023-08_ASPB.md), so
sorting by file path sorts chronologically. `people-list.html`'s own sort_by
option only understands 'title'/'date', so we pre-sort here instead and pass
the already-ordered list through (sort_by left unset, so it isn't re-sorted).
{% endcomment %}
{% assign sorted_news = site.news | sort: 'path' | reverse %}

<section class="page__content cf">

<div class="entries-{{ page.entries_layout }}">
  {% include people-list.html entries=sorted_news type=page.entries_layout %}
</div>
</section>
