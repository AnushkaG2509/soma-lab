---
title: HOME
nav:
  order: 1
---

### Welcome to the SOMa Lab

The SOMa Lab develops and applies next-generation single-cell and spatial multi-omics technologies, alongside advanced computational methods, to decode how cells organize and interact to sustain healthy tissues, and how these interactions collapse in disease.

### Our Approach

We connect clinical samples and patient-derived disease models with in-house developed spatial omic technologies, and biology‑ and measurement‑aware computational approaches to push the boundaries of what can be measured and understood in tissues, generating unprecedented insight into the cellular basis of health and disease.

Our work draws on concepts from bioinformatics, integrative multi-omics, spatial barcoding, assay development, quantitative optical imaging, and next-generation sequencing.

### Our Mission & Philosophy

We are a group of curiosity‑driven scientists motivated by problems that matter to researchers, biologists, and clinicians today. To identify and tackle the right questions, we rely on strong multi-institutional and multi-disciplinary collaborations spanning academia, hospitals, and industry partners. Our long-term goal is to translate our findings into actionable outcomes, enabling biomarker discovery, patient stratification, and therapeutic development.

{% include section.html %}

## Explore SOMa Lab

{% capture text %}

We are developing novel single-cell and spatial multi-omics technologies, together with advanced computaional methods to push the boundary of what can be measured and understood in tissues. We are using these methods to focus on diverse areas of biology such as adipose tissue dysfunction in diabetes, immuno-oncology, and cancer metastasis & therapy resistance. Learn more about the technology, our developed computational methods and how we apply it to research problems here.

{%
  include button.html
  link="projects"
  text="Browse our projects"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/research.png"
  link="projects"
  title="Our Research"
  flip=true
  style="bare"
  text=text
%}

{% capture text %}

Our publications span technology development, computational methods, and disease-focused studies. Read more about our recent work on a new spatial transcriptomics platform, adipose tissue dysfunction in obesity, and integrative analysis of scRNA-seq and snRNA-seq datasets.
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
  image="images/publication_2.png"
  link="research"
  title="Our Publications"
  text=text
%}


{% capture text %}

Prof. Anushka Gupta is the Principal Investigator of the SOMa Lab. As a new lab, we are actively looking for highly motivated and curious undergraduate, graduate (Masters/PhD), post-doctoral, and project associate candidates to join our team! Please [contact Prof. Gupta](mailto:agupta@iitm.ac.in) and include a CV with your research interests.

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
  image="images/team.png"
  link="team"
  title="Our Team"
  flip=true
  style="bare"
  text=text
%}

{% capture text %}

We are always looking to collaborate with researchers, biologists, and clinicians to identify biological questions where spatial context, multimodal measurements, and integrative analysis are essential for new insights. To explore potential collaborations, reach out at agupta@iitm.ac.in. 

{%
  include button.html
  link="contact"
  text="Contact us"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/colab.png"
  link="contact"
  title="Collaborators and Partnerships"
  text=text
%}
