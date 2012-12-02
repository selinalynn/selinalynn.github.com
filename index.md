---
layout: page
title: Hello World!
tagline: Supporting tagline
---
{% include JB/setup %}

回忆昨日的忧愁.

最近的schedule:

* 把翻译课的翻译句子都背出来

* 高德的翻译和词形转换都搞清楚

* 记得在博客上码点文字上去

* 记得把CNAME加好

* 记得付款

感觉差不多也就这些了,看起来很少,但是做起来也不少了,恩.

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
