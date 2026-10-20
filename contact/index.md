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
  link="[https://www.google.com/maps](https://www.google.com/maps/place/Cha+University+-+Bundang+Medical+Center/data=!3m1!4b1!4m4!3m3!1s0x357ca7e0195017f5:0x54576f7c6aced8a1!16s%2Fg%2F12vs01w8g!20s8Q99C46G%2B458?entry=ttu&g_ep=EgoyMDI2MTAxNC4wIKXMDSoASAFQAw%3D%3D)"
%}

{% include section.html %}

{% capture col1 %}

{%
  include figure.html
  image="images/CBC.jpg"
  caption="Lorem ipsum"
%}

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="images/MedicalCenter.jpg"
  caption="Lorem ipsum"
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
