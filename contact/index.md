---
title: Contact
nav:
  order: 5
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

If you are interested in our work, or in positions in the lab, please get in touch!

{%
  include button.html
  type="email"
  text="lmandevi@nmu.edu"
  link="lmandevi@nmu.edu"
%}


{% include section.html %}

{% capture col1 %}

{%
  include figure.html
  image="images/harlow.jpg"
  caption="Harlow Lake in fall"
%}

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="images/agpond.jpg"
  caption="A deceptively beautiful pond in the midst of a soybean field"
%}

{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}

{% include section.html dark=true %}

{% capture col1 %}
Fish
{% endcapture %}

{% capture col2 %}
Genetics
{% endcapture %}

{% capture col3 %}
Other cool stuff
{% endcapture %}

{% include cols.html col1=col1 col2=col2 col3=col3 %}
