---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

The Haystead Laboratory at Duke University School of Medicine is a multidisciplinary research group uniting faculty, postdoctoral scholars, staff scientists, and trainees across chemistry, biology, medical physics, and computational sciences.

{% include section.html %}

{% include list.html data="members" component="portrait" filter="role == 'principal-investigator'" %}
{% include list.html data="members" component="portrait" filter="role != 'principal-investigator'" %}

{% include section.html background="images/background.jpg" dark=true %}

We work with a wide range of outstanding groups from around the world, and we’re always on the lookout for new and unique perspectives. We want to push the frontier of data science and train the next generation of data scientists.

{% include section.html %}

{% capture content %}

{% include figure.html image="images/chem.jpg" %}
{% include figure.html image="images/data2.jpg" %}
{% include figure.html image="images/vic.jpg" %}
{% include figure.html image="images/tay.jpg" %}
{% include figure.html image="images/tim.jpg" %}
{% include figure.html image="images/kesh.jpg" %}
{% include figure.html image="images/dave.jpg" %}
{% include figure.html image="images/lau.jpg" %}

{% endcapture %}

{% include grid.html style="square" content=content %}
