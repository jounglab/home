---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

Our team brings together researchers with backgrounds in bioinformatics, molecular biology, and data science.
We work closely with clinicians and experimental biologists to turn large-scale genomic data into biological insight and clinically useful biomarkers.

{% include section.html %}

{% include list.html data="members" component="portrait" filter="role == 'principal-investigator'" %}
{% include list.html data="members" component="portrait" filter="role == 'postdoc'" %}
{% include list.html data="members" component="portrait" filter="role == 'phd'" %}
{% include list.html data="members" component="portrait" filter="role == 'researcher'" %}
{% include list.html data="members" component="portrait" filter="role == 'ms'" %}
{% include list.html data="members" component="portrait" filter="role == 'undergrad'" %}

## Alumni
{% include list.html data="members" component="portrait" filter="role == 'alumni'" %}

{% include section.html background="images/background.jpg" dark=true %}

## Join Us

We are always looking for motivated graduate students, postdoctoral researchers, and undergraduate interns interested in computational genomics, multi-omics integration, and AI-driven biomedical research.

{% include button.html link="contact" text="Contact us" icon="fa-solid fa-arrow-right" flip=true %}

{% include section.html %}

## Lab Life

{% capture content %}

{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}

{% endcapture %}

{% include grid.html style="square" content=content %}
