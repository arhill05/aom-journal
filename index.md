---
layout: home
---

## The Art of Manliness Journal Jumpstart

Here are my random ramblings that try to follow along with the points illustrated in the [Art of Manliness Journaling Challenge](https://www.artofmanliness.com/articles/jumpstart-your-journaling-a-31-day-challenge/). Feel free to leave any feedback you may have, or just start a conversation with me at [me@andrewhill.io](mailto:me@andrewhill.io).

>Doing something for around 30 days is a great way to not only build a habit, but to also explore if it’s right for you. Maybe journaling isn’t for you, and you just have never taken the time to really prove that to yourself. Or maybe you love the practice, and simply haven’t gotten into the habit yet.

<ul class="post-list">
  {% for post in site.posts %}
    <li class="post">
    <small>{{ post.date  | date: "%-d %B %Y" }}</small>
      <h2><a href="{{ post.url | relative_url }}">{{ post.title }}</a></h2>
      {{ post.subtitle }}
    </li>
  {% endfor %}
</ul>