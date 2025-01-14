---
title: Members
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Depledge Lab Members

The Depledge lab welcomes people of any race, ethnicity, religion, national origin, gender identity, gender expression, caregiver and family commitments, political affiliation, sexual orientation, and eligible age or disability status.
See our lab compact and philosophy [TODO add Link/Site].

{% include section.html %}

{% include list.html data="members" component="portrait" filters="role: pi, group: " %}
{% include list.html data="members" component="portrait" filters="role: postdoc, group: " %}
{% include list.html data="members" component="portrait" filters="role: phd, group: " %}
{% include list.html data="members" component="portrait" filters="role: postgradres, group: " %}
{% include list.html data="members" component="portrait" filters="role: postgrad, group: " %}
{% include list.html data="members" component="portrait" filters="role: undergrad, group: " %}
{% include list.html data="members" component="portrait" filters="role: programmer, group: " %}
{% include list.html data="members" component="portrait" filters="role: mascot, group: " %}

{% include section.html background="images/background_dna.jpg" dark=true %}

Interested in joining the Depledge Lab Team?

{%
  include button.html
  icon="fa-solid fa-handshake-angle"
  text="Join the Team"
  link="join"
  style="button"
%}

{% include section.html %}

## Alumni

Past members of the Depledge Lab.

{% include list.html data="members" component="portrait" filters="role: pi, group: alum" style="small" %}
{% include list.html data="members" component="portrait" filters="role: postdoc, group: alum" style="small" %}
{% include list.html data="members" component="portrait" filters="role: phd, group: alum" style="small" %}
{% include list.html data="members" component="portrait" filters="role: postgradres, group: " %}
{% include list.html data="members" component="portrait" filters="role: postgrad, group: " %}
{% include list.html data="members" component="portrait" filters="role: undergrad, group: alum" style="small" %}
{% include list.html data="members" component="portrait" filters="role: programmer, group: alum" style="small" %}
{% include list.html data="members" component="portrait" filters="role: mascot, group: alum" style="small" %}

{% include grid.html style="square" content=content %}
