---
layout: default
title: Posts
permalink: /posts/
---

<ul class="post-list">
    {% for post in site.posts %}
      <li>
        <h2>
          <a class="post-link" href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a>
        </h2>
          <h3><span class="post-meta">{{ post.date | date: "%A, %B %-d, %Y" }}</span></h3>
        <p class="post-excerpt">{{ post.content | strip_html | truncatewords: 25 }}</p>
        <h3><a class="comment-count" href="{{ post.url | prepend: site.baseurl }}#disqus_thread">Comments</a></h3>
      </li>
    {% endfor %}
  </ul>
