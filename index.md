---
layout: page
title: Linux德语学习札记
tagline: 好好学习,天天向上
---
{% include JB/setup %}

>Jeder hat seinen Lieblingsfeind, ohne den er einsam wäre.
>
> --Romain Gary,französischer Romanschriftsteller

最近的schedule:

				1. 把翻译的句子都背出来
				2. 把高德翻译都背出来
				3. 在博客上改点东西
				4. 记得改cname
				5. 把欠的各种都还掉

1.  好忧伤



2.  好忧伤


感觉差不多也就这些了,看起来很少,但是做起来也不少了,恩.

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
