---
title: HOME
nav:
  order: 1
---

### What We Do

Welcome to the SOMa Lab at IIT Madras! Our lab develops and applies next-generation spatial multi-omics technologies to study human health and disease. Using ethically sourced human samples and patient-derived disease models, we investigate how cells of different types and states are organized within tissues, how they interact to maintain homeostasis, and how these interactions are disrupted in disease. Our work integrates spatial and single-cell multi-omics, high-resolution imaging, next-generation sequencing, and computational methods for multimodal data analysis.

### Our Mission & Philosophy

Our research is driven by clinically urgent problems that are affecting patients today. We operate at the interface of basic, translational, and clinical research, using clinically informed questions to guide tool development. Through close collaboration with clinicians, hospitals, and industry partners, our goal is to translate spatial multi-omics insights into actionable outcomes—enabling biomarker discovery, patient stratification, and therapeutic development that ultimately improve patient care.


{% include section.html %}

## Explore SOMa Lab

{% capture text %}

We are using spatial-multiomics tools to investigate some of the most pressing issues, including cancer metastasis and therapy resistance, lung remodeling in response to air pollutants, and adipose tissue dysfunction in diabetes. Learn more about the technology and how we apply it to research problems here.

{%
  include button.html
  link="research"
  text="Browse our projects"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="research"
  title="Our Research"
  flip=true
  style="bare"
  text=text
%}

{% capture text %}

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.

{%
  include button.html
  link="research"
  text="See our publications"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="research"
  title="Our Research"
  text=text
%}


{% capture text %}

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.

{%
  include button.html
  link="team"
  text="Meet our team"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="team"
  title="Our Team"
  text=text
%}
