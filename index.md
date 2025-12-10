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

{% for post in site.posts %}
  <div class="project-box">
    <img src="{{ post.image }}" alt="{{ post.image-alt }}"/>
    <div class="project-title">
      <a href="{{ post.url }}">{{ post.title }}</a>
    </div>
    <span class="project-category">
        {{ post.categories | join: ', ' }}
    </span>
    <p>{{ post.excerpt }}</p>
  </div>
{% endfor %}

