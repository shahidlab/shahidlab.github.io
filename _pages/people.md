---
layout: single
classes: wide
title: Team
header:
  #overlay_color: "#111"
  overlay_image: /assets/images/ath3.jpg
  og_image: /assets/images/saima-shahid.jpg # social/search share image for this page -- her photo, not the banner
  og_image_alt: "Dr Saima Shahid, Principal Investigator, Shahid Lab, University of Sheffield"
permalink : /people/
collection: people
entries_layout: grid
#classes: wide
show_excerpts: true
author_profile: false
---
<h2  style="margin-top: 0">Principal Investigator</h2>

<div class="clearfix-block" markdown="1">
![Dr Saima Shahid]({{ site.url }}{{ site.baseurl }}/assets/images/saima-shahid.jpg){: .align-left .pi-photo}  
### [Dr Saima Shahid](https://www.sheffield.ac.uk/biosciences/people/saima-shahid)

[Lecturer | Plants, Photosynthesis and Soil Cluster](https://sheffield.ac.uk/biosciences/research/clusters/plants-photosynthesis-and-soil/pps-members)   
School of Biosciences, University of Sheffield  
Office: C62, Alfred Denny Building   
Lab: C45, Alfred Denny Building

[Saima's CV]({{ site.url }}{{ site.baseurl }}/assets/CV_Saima_Shahid_2026.pdf)  <a title='Email' href="mailto:saima.shahid@okstate.edu">
  <i class="fas fa-envelope fa-fw" style="color:#000000"></i></a>
<a href="http://scholar.google.com/citations?user=lez4bcIAAAAJ&hl=en" itemprop="sameAs" rel="nofollow noopener noreferrer">
  <i class="fab fa-google" aria-hidden="true" style="color:#4c8bf5"> </i></a>
<a href="https://orcid.org/0000-0001-9385-0925" itemprop="sameAs" rel="nofollow noopener noreferrer">
  <i class="fas fa-info-circle" aria-hidden="true" style="color:#ABC953"></i></a>
<a title="LinkedIn" href="https://www.linkedin.com/in/saima-shahid" itemprop="sameAs" rel="nofollow noopener noreferrer">
  <i class="fab fa-fw fa-linkedin" style="color:#0077B5"></i></a>
<a title="Twitter" href="https://twitter.com/psaima">
  <i class="fab fa-fw fa-twitter" style="color:#00acee"></i></a>  
</div>

## Current Members
<section class="page__content cf">

<div class="entries-{{ page.entries_layout }}">
  {% include people-list.html entries=site.people sort_by=page.sort_by sort_order=page.sort_order type=page.entries_layout %}
</div>
</section>

## Alumni
<section class="page__content cf">
  {% include alumni-gallery.html entries=site.alum %}
</section>
