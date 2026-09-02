---
layout: splash
hidden: true
permalink: /
header:
  image: /assets/images/ath3.jpg
feature_row:
  - image_path: /assets/images/spring-2022.jpg
    alt: "lab photo"
    title: "How do plants communicate with other organisms?"
    excerpt: "We investigate how mobile small RNAs and epigenetic memory shape plant responses during interspecies interactions. By uncovering the molecular messages underlying these interactions, we aim to reveal new principles of plant defence, develop RNA-based approaches to protect crops from parasitic plants, and enhance beneficial interactions with symbionts."
    btns:
      - url: /research/
        label: "Explore our research"
        class: "btn--brand-blue"
      - url: /people/
        label: "Meet the lab members"
        class: "btn--brand-green"
      - url: /join/
        label: "Join us"
        class: "btn--brand-yellow"
feature_row2:
  - image_path: /assets/images/Shahidlab-logo-swirl-color2-notext.gif
    alt: "Arabidopsis leaf"
    title: "Interspecies RNAi"
    excerpt: "We study the mechanisms underlying biogenesis, transfer and role of mobile small RNAs in interspecies communication, with the aim of developing synthetic RNA interference-based solutions for crop protection."
    url: /research/#interspecies
    btn_label: "Learn more"
    btn_class: "btn--external"
  - image_path: /assets/images/chromatin.png
    alt: "non genic elements in the genome"
    title: "Epigenetic memory"
    excerpt: "We investigate how plant interactions with parasites and symbionts reshape epigenomic regulatory landscapes -- asking how new chromatin states form, whether they persist after the interaction has ended, and whether they alter future responses."
    url: /research/#memory
    btn_label: "Learn more"
    btn_class: "btn--external"
  - image_path: /assets/images/cuscuta.png
    alt: "Cuscuta, a parasitic plant, flowering on its host"
    title: "Genome plasticity in plant parasitism"
    excerpt: "The intimate association of parasitic plants with their hosts creates opportunities for horizontal gene transfer between host and parasite genomes. We study how such horizontally transferred DNA is recognised, epigenetically regulated, and sometimes repurposed into new regulatory functions."
    url: /research/#plasticity
    btn_label: "Learn more"
    btn_class: "btn--external"
---
# THE SHAHID LAB
{: style="text-align: center;
  letter-spacing: 0.25em;"}

{% include feature_row type="left" %}  
## Research Program

{% include feature_row id="feature_row2" %}

## Latest News

{% comment %}
GitHub Pages' safe mode blocks the jekyll-paginate/custom-plugin approaches
to "recent posts on a non-post page", so this pre-sorts and slices the
collection in Liquid instead (the workaround from
https://github.com/mmistakes/minimal-mistakes/issues/1251), then reuses the
same people-list.html/people-single.html rendering the News page itself uses
(see _pages/news.md) so these cards look and behave identically to that page.
{% endcomment %}
{% assign latest_news = site.news | sort: 'path' | reverse | slice: 0, 4 %}

<div class="entries-grid">
  {% include people-list.html entries=latest_news type="grid" %}
</div>

[All news &rarr;]({{ site.baseurl }}/news/){: .btn .btn--external}
