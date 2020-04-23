---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
---
{% for post in site.posts %}
  <div class="post-preview">
    <a href="{{ post.url | relative_url }}">
      <h2 class="post-title">
        {{ post.title }} 
      </h2>
      <h3 class="post-subtitle">
        {{ post.excerpt }}
      </h3>
    </a>
    <p class="post-meta">Posted by
      <a href="#">Start Bootstrap</a>
      on September 24, 2019</p>
  </div>
  <hr>
{% endfor %}

