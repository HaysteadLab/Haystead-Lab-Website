---
title: Contact
nav:
  order: 5
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

Our Lab is part of the Duke University School of Medicine. We are located in the Levine Science Reaserch Center in building C of the first floor. 

{%
  include button.html
  type="email"
  text="david.loiselle@duke.edu"
  link="david.loiselle@duke.edu"
%}
{%
  include button.html
  type="phone"
  text="(919) 681 8020"
  link="+1-919-681-8020"
%}
{%
  include button.html
  type="address"
  tooltip="Our location on Google Maps for easy navigation"
  link="https://maps.app.goo.gl/HC9Lv7ntk8Qkz7nn6"
%}

{% include section.html %}

{% capture col1 %}

{%
  include figure.html
  image="images/tumor.jpeg"
  caption="Diagnostic PET image of a mouse with agressive tumors"
%}

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="images/c1.png"
  caption="Blebbing observed in breast cancer cell line"
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
