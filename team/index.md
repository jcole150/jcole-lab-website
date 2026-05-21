```markdown
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

## Alumni

<table class="alumni-table">
  <thead>
    <tr>
      <th>Name</th>
      <th>Lab role</th>
      <th>Dates</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Moomal Jatoi, MS</td>
      <td>MS graduate student</td>
      <td>2025–2026</td>
    </tr>
  </tbody>
</table>

<style>
.alumni-table {
  width: 100%;
  border-collapse: collapse;
  margin: 1rem auto 2rem auto;
}

.alumni-table,
.alumni-table tr,
.alumni-table th,
.alumni-table td {
  border: none !important;
}

.alumni-table th,
.alumni-table td {
  padding: 0.5rem 1rem;
  text-align: left;
}

.alumni-table th {
  font-weight: 700;
}
</style>

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
  link6="https://www.watermelon.org/audiences/industry/research/"
  tooltip6="National Watermelon Promotion Board"

%}
```
