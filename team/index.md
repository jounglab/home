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

## Undergraduate Intern
2026 
Jihu Jung (Senior), Yubin Soung (Senior), Doo-Hyun Eom (Junior), Eun-Bin Jung (Sophomore)

2025 
Ji-Young Lee (Junior), Suho Kim (Senior), Chae-Hyun Kim (Senior), Yudam Shin (Senior)

2024 
Ji-Yeon Hong (Senior), Sun-Young Oh (Senior), Yeon-Woo Lee (Senior) 

2023 
Hee-Seung Ban (Senior), Daewon Shim (Senior), Do-Kyung Yoon (Senior), Ho-Jun Sung (Senior)

2022
Young-Yoon Kim (Freshman), Soel Jeong (Senior), Jong-Heon Park (Senior), Jeong-Eon Park (Senior)

2021
Hye-Bin Ahn (Sophomore), Hyo-Eun Lee (Sophomore)

{% include section.html %}

## Lab Life

{% capture content %}

{% include figure.html image="images/photo_lab001.jpg" %}
{% include figure.html image="images/photo_lab002.jpg" %}
{% include figure.html image="images/photo_lab003.jpg" %}
{% include figure.html image="images/photo_lab004.jpg" %}

{% endcapture %}

{% include section.html %}

## Join Us

We are always looking for motivated graduate students, postdoctoral researchers, and undergraduate interns interested in computational genomics, multi-omics integration, and AI-driven biomedical research.

{% include button.html link="contact" text="Contact us" icon="fa-solid fa-arrow-right" flip=true %}

{% include grid.html style="square" content=content %}
