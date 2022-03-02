## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/nathanchoui/nathan.github.io/edit/gh-pages/index.md) to maintain and preview the content for your website in Markdown files.



<ul>
{% for post in site.posts %}
<li>
<a href="{{ post.url }}">{{ post.title }}</a>
</li>
{% endfor %}
</ul>

