---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

The Mandeville Lab includes graduate students and undergraduates at NMU and several members based at the University of Guelph. We also have a few "friends of the lab" who defy classification, but we love them so you'll find info about them here. We're proud of our alumni too - look below to see what they're up to now!

Note, this page is under construction and does not yet include everyone who should be here. 

# {% include icon.html icon="fa-solid fa-users" %}Current lab members
{% include section.html %}

{% include list.html data="members" component="portrait" filter="role == 'pi'" %}
{% include list.html data="members" component="portrait" filter="role != 'pi' && role != 'alum'" %}

{% include section.html background="images/background.jpg" dark=true %}

If you're interested in joining the lab as a graduate student (MS) or undergraduate researcher, please contact Liz Mandeville

# {% include icon.html icon="fa-solid fa-users" %}Lab Alumni

These folks have moved on to new adventures. See what each of them is doing below!
{% include list.html data="members" component="portrait" filter="role == 'alum'" %}
{% include section.html %}

{% capture content %}

{% include figure.html image="images/harlow.jpg" %}
{% include figure.html image="images/nfbridge.jpg" %}
{% include figure.html image="images/winds.jpg" %}

{% endcapture %}

{% include grid.html style="square" content=content %}
