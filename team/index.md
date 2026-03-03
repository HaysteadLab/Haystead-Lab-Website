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

{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}

{% endcapture %}

{% include grid.html style="square" content=content %}
