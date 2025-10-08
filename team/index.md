---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

{% include section.html %}

{% include list.html data="members" component="portrait" filter="role == 'principal-investigator' and role != 'collaborator'" style="small" %}
{% include list.html data="members" component="portrait" filter="role != 'principal-investigator' and role != 'collaborator'" style="small" %}

# {% include icon.html icon="fa-solid fa-users" %}Collaborators

{% include section.html %}

{% include list.html data="members" component="portrait" filter="role == 'collaborator'" style="small" %}