---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# <i class="fas fa-users"></i>Team

{% include section.html %}

{% include list.html data="members" component="portrait" filters="role: pi, group: " %}
{% include list.html data="members" component="portrait" filters="role: postdoc, group: " %}
{% include list.html data="members" component="portrait" filters="role: phd, group: " %}
{% include list.html data="members" component="portrait" filters="role: undergraduate student, group: " %}
{% include list.html data="members" component="portrait" filters="role: graduate student, group: " %}
{% include list.html data="members" component="portrait" filters="role: pra, group: " %}
{% include list.html data="members" component="portrait" filters="role: mascot, group: " %}

{:.center}

{% include section.html dark=true %}

<!-- ## Join the Cole Lab! -->
{:.center}
<!-- Come join us as we grow the lab -->
{:.center}

{%
  include link.html
  icon="fas fa-hands-helping"
  text="Join the Team"
  link="join"
  style="button"
%}
{:.center}

{% include section.html %}

## Alumni
{% include list.html data="members" component="portrait" filters="role: pi, group: " %}
{% include list.html data="members" component="portrait" filters="role: postdoc, group: " %}
{% include list.html data="members" component="portrait" filters="role: phd, group: " %}
{% include list.html data="members" component="portrait" filters="role: undergraduate student, group: " %}
{% include list.html data="members" component="portrait" filters="role: graduate student, group: " %}
{% include list.html data="members" component="portrait" filters="role: pra, group: " %}
{% include list.html data="members" component="portrait" filters="role: mascot, group: " %}

## Alumni

<table class="alumni-table">
  <thead>
    <tr>
      <th>Name</th>
      <th>Lab role</th>
      <th>Dates</th>
      <th>Current position</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>First Last</td>
      <td>Undergraduate student</td>
      <td>2023–2024</td>
      <td>Medical student, University X</td>
    </tr>
    <tr>
      <td>First Last</td>
      <td>Professional Research Assistant</td>
      <td>2022–2025</td>
      <td>PhD student, University Y</td>
    </tr>
  </tbody>
</table>

{% include section.html dark=true %}

## Funding

Our work is made possible by funding from several organizations.
{:.center}

{%
  include gallery.html

  image1="images/funding/ADA.jpg"
  link1="https://diabetes.org/"
  tooltip1="American Diabetes Association"

  image2="images/funding/NIDDK.jpg"
  link2="https://www.niddk.nih.gov/"
  tooltip2="National Institute of Diabetes and Digestive and Kidney Diseases"

  image3="images/funding/lfcwhr_h_clr_rgb copy.jpg"
  link3="https://medschool.cuanschutz.edu/center-for-womens-health-research"
  tooltip3="Ludeman Family Center for Women's Health Research"
  
  image4="images/funding/TRSP.jpg"
  link4="https://medschool.cuanschutz.edu/program-to-advance-physician-scientists-translational-research/physician-scientist-initiatives/Early-faculty-TRSP"
  tooltip4="Translational Research Scholars Program"
  
  image5="images/funding/NIGMS_v2.jpg"
  link5="https://medschool.cuanschutz.edu/center-for-womens-health-research"
  tooltip5="National Institute of General Medical Sciences"

  image6="images/funding/watermelon.png"
  link6="https://medschool.cuanschutz.edu/center-for-womens-health-research](https://www.watermelon.org/audiences/industry/research/"
  tooltip6="National Watermelon Promotion Board"


%}
