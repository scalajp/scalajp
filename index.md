---
layout: default
root: ./
title: 日本Scalaユーザーズグループ
---

<div class="hero-unit">
    <h1 class="top-h1">日本Scalaユーザーズグループ</h1>
    <p>日本Scalaユーザーズグループでは、Scalaのより一層の普及を目指しています。</p>
</div>

<div>
    {% for post in site.posts limit:3 %}
    <h3><a href="{{ page.root }}{{ post.url }}">{{ post.title }}</a></h3>
    <div>{{ post.date | date_to_string }}</div>
    <div>{{ post.content }}</div>
    {% endfor %}
</div>

#### [過去の記事を読む]({{ page.root }}news.html)