---
tite: Here's a list of projects
---

{% for project in site.projects %}
  <h2>{{ project.title }}</h2>
  <p>This project is from <b>{{project.first_month}}</b></p>
{% endfor %}
