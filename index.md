---
layout: default
root: ./
title: 日本Scalaユーザーズグループ
---

<div class="hero-unit">
    <h1 class="top-h1">日本Scalaユーザーズグループ</h1>
    <p>日本Scalaユーザーズグループでは、Scalaのより一層の普及を目指しています。</p>
</div>

<div id="home">
    <ul class="posts">
        {% for post in site.posts %}
        <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ post.url }}">{{ post.title }}</a></li>
        {% endfor %}
    </ul>
</div>
