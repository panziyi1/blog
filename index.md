# All about Cinema-prompt

# How to
## Make a software package distribution
{% assign doclist = site.data.mainpage.docs | sort: 'title'  %}
{% for item in doclist %}
[{{item.title}}]({{site.baseurl}}/{{item.url}})
{% endfor %}

# About
{% include about.md %}