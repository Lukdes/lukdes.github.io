---
layout: default
---
# Hi!
_placeholder text_

_write something about your academic & work experience_

_write something about interests / desired roles_

To learn more about me and how to reach out, click [here](./about-me.html).

You can also view my resume [here](/assets/resume.pdf).

# Featured Projects

{% for project in site.projects %}
  <div class="project-box">
    <img src="{{ project.image }}" alt="{{ project.image-alt }}"/>
    <div class="project-title">
      <a href="{{ project.url }}">{{ project.title }}</a>
    </div>
    <span class="project-category">
        {{ project.categories | join: ', ' }}
    </span>
    <p>{{ project.excerpt }}</p>
  </div>
{% endfor %}
