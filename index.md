# Welcome to My GitHub Pages Blog!

이곳은 **Markdown만**으로 만든 블로그입니다.

{% for post in site.posts limit:5 %}
- [{{ post.title }}]({{ post.url }})
{% endfor %}

- [About]({% link _pages/home.md %})
- [Contact](contact.md)
- [Blog Post 1](post1.md)
- [Blog Post 2](post2.md)
