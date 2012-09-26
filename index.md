---
layout: page
title:  Welcome
tagline: Daniel Ho Welcome it is using master instead 
---
{% include JB/setup %}

## Today 12 Aug 2012
- researching UI IOS menus again

    $ rm -rf _posts/core-samples

Here's a sample "Hello World".

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>



