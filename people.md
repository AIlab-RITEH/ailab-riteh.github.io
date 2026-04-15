---
layout: single
title: Our Team
permalink: /people/


# Faculty section -- Principal Investigators
# [IMPORTANT!] Don't forget to upload the corresponding photo to /assets/images/people/!
# To add a new faculty member, just copy-paste the template below and edit accordingly
faculty:
  # <TEMPLATE BEGIN>
  # - image_path: /assets/images/people/[lastname.jpg]
  #   alt: "[Prof. FirstName LastName]"
  #   title: "[Prof. FirstName LastName, Ph.D.]"
  #   excerpt: |
  #     **[Position/Title]**
  #     
  #     Research: [Research interests]
  #
  #     [Scholar]([google-scholar-url])
  #
  #     [Email](mailto:[email]) • [Website]([personal-website]) • [+385 XX XXX XXX](tel:+385XXXXXXXXX)
  # </TEMPLATE END>
  - image_path: /assets/images/people/stajduhar.jpg
    alt: "Prof. Ivan Štajduhar"
    title: "Prof. Ivan Štajduhar, Ph.D."
    excerpt: |
      **Professor / Lab Head**
      
      Research: Machine Learning, Medical Image Analysis, AI

      [Scholar](https://scholar.google.com/citations?user=xBWDZPYAAAAJ&hl=en&oi=ao)

      [Email](mailto:ivan.stajduhar@uniri.hr) • [Website](https://istajduh.github.io/) • [+385 51 651 448](tel:+38551651448)

# Postdocs section
postdocs:
  # <TEMPLATE BEGIN>
  # - image_path: /assets/images/people/[lastname.png]
  #   alt: "Dr. [FirstName LastName]"
  #   title: "Dr. [FirstName LastName]"
  #   excerpt: |
  #     **Postdoctoral Researcher**
  #     
  #     Research: [Research interests]
  #     
  #     [Email](mailto:[email]) • [Scholar]([google-scholar-url])
  # </TEMPLATE END>
  - image_path: /assets/images/people/hrzic.png
    alt: "Dr. Franko Hržić"
    title: "Dr. Franko Hržić"
    excerpt: |
      **Postdoctoral Researcher**
      
      Research: Computer Vision, Deep Learning, Medical Imaging
      
      [Email](mailto:franko.hrzic@riteh.uniri.hr) • [Scholar](https://scholar.google.com/citations?user=Zs4lZCoAAAAJ&hl=en&oi=ao)
  - image_path: /assets/images/people/napravnik.png
    alt: "Dr. Mateja Napravnik"
    title: "Dr. Mateja Napravnik"
    excerpt: |
      **Postdoctoral Researcher**
      
      Research: Deep Learning, Medical Imaging, Transfer Learning
      
      [Email](mailto:mateja.napravnik@riteh.uniri.hr) • [Scholar](https://scholar.google.com/citations?user=kXNxetQAAAAJ&hl=en&oi=ao)

# Associates section -- PhD Students and Research Associates
# [IMPORTANT!] Don't forget to upload the corresponding photo to /assets/images/people/!
# to add a new associate, just copy-paste the template below and edit accordingly

associates:
  # <TEMPLATE BEGIN>
  # - image_path: /assets/images/people/[lastname.png]
  #   alt: "[FirstName LastName]"
  #   title: "[FirstName LastName]"
  #   excerpt: "[PhD Student / Research Associate / Master Student]"
  # </TEMPLATE END>
  - image_path: /assets/images/people/krajci.png
    alt: "Mária Krajčí"
    title: "Mária Krajčí"
    excerpt: "PhD Student"
  # Skoki is commented out - he will not be shown in the website
  # - image_path: /assets/images/people/skoki.png
  #   alt: "Arian Skoki"
  #   title: "Arian Skoki"
  #   excerpt: "PhD Student"
  - image_path: /assets/images/people/mikulic.png
    alt: "Mateo Mikulić"
    title: "Mateo Mikulić"
    excerpt: "PhD Student"
  - image_path: /assets/images/people/vicevic.png
    alt: "Dominik Vičević"
    title: "Dominik Vičević"
    excerpt: "PhD Student"
  - image_path: /assets/images/people/manojlovic.png
    alt: "Teo Manojlović"
    title: "Teo Manojlović"
    excerpt: "PhD Student"
  - image_path: /assets/images/people/ilijanic.png
    alt: "Luka Ilijanić"
    title: "Luka Ilijanić"
    excerpt: "Research Associate"

# This is a gallery with equipment. (docs and info about Minimal Mistakes galleries: https://mmistakes.github.io/minimal-mistakes/post%20formats/post-gallery/)
# For simplicity, keep image_path and url the same -- they're both image paths. 
# the difference between these two images is that one is a preview, and one will be shown in full display, "on click". 
research_equipment:
  - image_path: /assets/images/equipment/maestral.jpg
    url: /assets/images/equipment/maestral.jpg
    alt: "Maestral Workstation"
    title: "Maestral Workstation"
  - image_path: /assets/images/equipment/siroko.jpg
    url: /assets/images/equipment/siroko.jpg
    alt: "Široko Server"
    title: "Široko Server"

# this is the same as research_equipment!
teaching_equipment:
  - image_path: /assets/images/equipment/bonaca.jpg
    url: /assets/images/equipment/bonaca.jpg
    alt: "Bonaca Workstation"
    title: "Bonaca Workstation"
  - image_path: /assets/images/equipment/dobot.jpg
    url: /assets/images/equipment/dobot.jpg
    alt: "Dobot"
    title: "Dobot"
  - image_path: /assets/images/equipment/diddyborg.jpg
    url: /assets/images/equipment/diddyborg.jpg
    alt: "DiddyBorg"
    title: "DiddyBorg"
  - image_path: /assets/images/equipment/meta2.jpg
    url: /assets/images/equipment/meta2.jpg
    alt: "Meta2"
    title: "Meta2"

# [YAML END]
---

## Principal Investigators
<div class="pis_feature_row">
{% include feature_row id="faculty" type="left" %}
</div>

---

## Postdoctoral Researchers
<div class="postdocs_feature_row">
  {% include feature_row id="postdocs" type="left" %}
</div>


## Associates & PhD Students
<div class="associates_feature_row">
  {% include feature_row id="associates" %}
</div>

## Alumni
### Former PhD students
- **Dr. Arian Skoki** - Research and Teaching Assistant

### Former Postdoctoral Researchers
- **Dr. Robert Baždarić** - Postdoctoral researcher

---

## Research Equpipment
{% include gallery id="research_equipment" %}

## Teaching Equpipment
{% include gallery id="teaching_equipment" %}

---

## Collaborators

We actively collaborate with researchers from:
- [Medical University of Graz](https://www.medunigraz.at/en/) (MedUni Graz), Graz, Austria
- [Faculty of Mathematics and Physics](https://www.fmf.uni-lj.si/en/), Ljubljana, Slovenia
- Various European institutions through Erasmus+ programs
- Industry partners in hospitality and healthcare sectors
