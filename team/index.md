---
title: Team
nav:
  order: 4
---

# Team

we are actively looking for highly motivated and curious undergraduate, graduate (Masters/PhD), post-doctoral, and project associate candidates to join our team! If you would like to join us, please contact Prof. Gupta ([agupta@iitm.ac.in](mailto:agupta@iitm.ac.in)) and include your CV with research interests. We welcome researchers from diverse backgrounds including biotechnology, computational biology, computer science, data science and related fields.

{% include section.html %}
## Principal Investigator

{% include photo_bio.html
  image="images/team.png"
  name="Prof. Anushka Gupta"
  subtitle="Assistant Professor"
  details="Department of Biotechnology<br> Indian Institute of Technology (IIT) Madras"
  size = "lg"
%}

{% include list.html data="members" component="portrait" filter="role == 'pi'" %}
{% include list.html data="members" component="portrait" filter="role != 'pi'" %}

{% include section.html background="images/background.jpg" dark=true %}

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor
incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis
nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

{% include section.html %}

{% capture content %}

{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}

{% endcapture %}

{% include grid.html style="square" content=content %}
