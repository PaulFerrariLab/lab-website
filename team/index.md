---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

{% include section.html %}

{% include list.html data="members" component="portrait" filter="role == 'principal-investigator'" style="tiny" %}
{% include list.html data="members" component="portrait" filter="role == 'engineer'" style="tiny" %}
{% include list.html data="members" component="portrait" filter="role == 'visiting-scientist'" style="tiny" %}
{% include list.html data="members" component="portrait" filter="role == 'tech'" style="tiny" %}
{% include list.html data="members" component="portrait" filter="role == 'epileptologist'" style="tiny" %}
{% include list.html data="members" component="portrait" filter="role == 'PhD Candidate | UT Austin'" style="tiny" %}
{% include list.html data="members" component="portrait" filter="role == 'MS Student | GVSU'" style="tiny" %}

{% include section.html %}
# {% include icon.html icon="fa-solid fa-users" %}Collaborators

{% include section.html %}

{% include list.html data="members" component="portrait" filter="role == 'collaborator'" style="tiny" %}
