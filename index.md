---
layout: page
title: Hugo's blog!
---

Follow my FB profile at: [Hugo's FB](https://www.facebook.com/hugosamuel.sanchezreyes)

## Author coordinates


    
Name : Hugo S. Sánchez-Reyes

e-mail : [hugo.geofisica@gmail.com](http://www.gmail.com)

github : hugosanrocks

Undergaduate Student at UJF France & IUSS Italy



## Diary

Here's my posts list.

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

## Stories & more ...

    <li><span>{{ Short stories }}</span> &raquo; <a href="{{ http://hugosanrocks.github.io/short%20stories.html }}">{{ post.title }}</a></li>

## To-Do

Please let me know any broken link or doubt releated to this site.
