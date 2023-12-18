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

<section class="page__content cf">

<div class="entries-{{ page.entries_layout }}">
  {% include people-list.html entries=site.news sort_by=page.sort_by sort_order=page.sort_order type=page.entries_layout %}
</div>
</section>
