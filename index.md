# Welcome to My GitHub Pages Blog!

이곳은 **Markdown만**으로 만든 블로그입니다.

{% raw %}
{% for post in site.posts limit:5 %}
- [{{ post.title }}]({{ post.url | relative_url }})
{% endfor %}
{% endraw %}

- [About]({% link _pages/home.md %})
- [Contact](contact.md)
- [Blog Post 1](post1.md)
- [Blog Post 2](post2.md)

이 페이지는 GitHub Pages를 사용하여 만들었습니다.

{% for post in site.posts limit:5 %}
- [{{ post.title }}]({{ post.url }})
{% endfor %}
