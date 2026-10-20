---
title: Contact
nav:
  order: 5
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

Contact information!

{%
  include button.html
  type="email"
  text="send"
  link="connectome@naver.com"
%}
{%
  include button.html
  type="phone"
  text="(031) 881-7182"
  link="+81-031-881-7182"
%}
{%
  include button.html
  type="address"
  tooltip="Our location on Google Maps for easy navigation"
  link="https://www.google.com/maps"
%}

{% include section.html %}

{% capture col1 %}

{%
  include figure.html
  image="images/MedicalCenter_map.jpg"
  caption="Bundang Cha Medical Center"
%}

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="images/CBC_map.jpg"
  caption="Cha Bio Complex"
%}

{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}

{% include section.html dark=true %}

{% capture col1 %}

{% endcapture %}

{% capture col2 %}

{% endcapture %}

{% capture col3 %}

{% endcapture %}

{% include cols.html col1=col1 col2=col2 col3=col3 %}
