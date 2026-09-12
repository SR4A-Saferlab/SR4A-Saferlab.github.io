---
title: Team
nav:
  order: 3
  tooltip: Who we are
---

# {% include icon.html icon="fa-solid fa-users" %}Team

SAFER Lab is led by the founders of SR4A and grows through collaboration: students, practitioners and partner agencies who want to work on evidence-based road safety. If that sounds like you, [get in touch](contact).

{% include section.html %}

## Leadership

{% include list.html data="members" component="portrait" filter="role == 'principal-investigator'" %}

{% include section.html background="images/background.jpg" dark=true %}

## Join us

We welcome collaborators at every stage: graduate students looking for research topics in crash analytics and machine learning, practitioners who want to bring our tools into their agency, and organizations interested in partnering on road safety in low- and middle-income countries.

{%
  include button.html
  link="contact"
  text="Contact us"
  icon="fa-solid fa-arrow-right"
  flip=true
%}

{% include section.html %}

{% include list.html data="members" component="portrait" filter="role != 'principal-investigator'" %}
