---
title: Members
nav:
  order: 2
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Depledge Lab Members

The Depledge lab welcomes people of any race, ethnicity, religion, national origin, gender identity, gender expression, caregiver and family commitments, political affiliation, sexual orientation, and eligible age or disability status.
See our lab [compact and philosophy](philosophy).

{% include section.html %}

{% include list.html data="members" component="portrait" filter="role == 'pi' and group != 'alum'" %}
{% include list.html data="members" component="portrait" filter="role == 'postdoc' and group != 'alum'" %}
{% include list.html data="members" component="portrait" filter="role == 'phd' and group != 'alum'" %}
{% include list.html data="members" component="portrait" filter="role == 'postgradres' and group != 'alum'" %}
{% include list.html data="members" component="portrait" filter="role == 'postgrad' and group != 'alum'" %}
{% include list.html data="members" component="portrait" filter="role == 'undergrad' and group != 'alum'" %}
{% include list.html data="members" component="portrait" filter="role == 'programmer' and group != 'alum'" %}
{% include list.html data="members" component="portrait" filter="role == 'mascot' and group != 'alum'" %}

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

{% include list.html data="members" component="portrait" filter="role == 'pi' and group == 'alum'" style="small" %}
{% include list.html data="members" component="portrait" filter="role == 'postdoc' and group == 'alum'" style="small" %}
{% include list.html data="members" component="portrait" filter="role == 'phd' and group == 'alum'" style="small" %}
{% include list.html data="members" component="portrait" filter="role == 'postgradres' and group == 'alum'" style="small" %}
{% include list.html data="members" component="portrait" filter="role == 'postgrad' and group == 'alum'" style="small" %}
{% include list.html data="members" component="portrait" filter="role == 'undergrad' and group == 'alum'" style="small" %}
{% include list.html data="members" component="portrait" filter="role == 'programmer' and group == 'alum'" style="small" %}
{% include list.html data="members" component="portrait" filter="role == 'mascot' and group == 'alum'" style="small" %}

