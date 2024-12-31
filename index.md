# All about Cinema-prompt

# How to
## Make a software package distribution
{% assign doclist = site.data.mainpage.docs | sort: 'title'  %}
{% for item in doclist %}
{% assign url = {{item.url}} %}
[{{item.title}}]( {% link url %} )
{% endfor %}

# About
{% include about.md %}