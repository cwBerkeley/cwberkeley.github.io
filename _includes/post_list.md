{% for post in site.posts %}
{{ DIVIDER }}
*{{ post.date | date_to_long_string}}*

### [{{ post.title }}]({{ site.url }}{{ post.url }})

{{ post.content }}

{% assign DIVIDER = "---" %}
{% endfor %}

