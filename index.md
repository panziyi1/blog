# All about Cinema-prompt

# How to
## Make a software package distribution
{% assign doclist = site.data.mainpage.docs | sort: 'title'  %}
{% for item in doclist %}
[{{item.title}}]({% link conda.md %})
{% endfor %}

# About
{% include about.md %}