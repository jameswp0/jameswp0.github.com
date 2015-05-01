---
layout: page
title: Beyond LMS
tagline: Learning Beyond the LMS
---
{% include JB/setup %}

  <p> 
    These pages are in progress. They will be devoted to:
    <ol>
      <li>Giving people who want to teach beyond the LMS a place where they can find tools, ideas, methodologies, and support... </li>
      <li>Giving people who create tools that do not depend upon a LMS a place to share those tools.</li>
    </ol>
    More information will appear as we go, but for now, you might want to check out our <a href="clatoolkit.html">first page</a>
    </p>

#####Recent Posts

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

