---
 layout: page
---

## Team

The following people are members of our research team:

{% for team_member in site.team_members %}
- **Name:** {{ team_member.name }}, **role:** {{ team_member.role }}
{% endfor %}
