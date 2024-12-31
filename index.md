# All about Cinema-prompt

# How to
## Make a software package distribution
{% assign doclist = site.data.mainpage.docs | sort: 'title'  %}
{% for item in doclist %}
{% assign url = {% link {{item.url}} %} %}
[{{item.title}}]({{url}})
{% endfor %}

# About
{% include about.md %}