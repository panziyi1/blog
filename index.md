# All about Cinema-prompt

# How to
## Make a software package distribution
{% assign doclist = site.data.samplelist.docs | sort: 'title'  %}
{% for item in doclist %}
[{{item.title}}]( {{item.url}} )
{% endfor %}

# About
{% include about.md %}