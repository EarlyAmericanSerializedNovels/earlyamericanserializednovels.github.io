---  
permalink: /novels/  
title: "Novels"  
excerpt: "Collection of novels displayed by ?organizaion choice?."  
layout: year-archive  
---  

<h3 class="archive__subtitle">{{ site.data.ui-text[site.locale].recent_posts | default: "Recent Posts" }}</h3>

{% for post in paginator.posts %}
  {% include archive-single.html %}
{% endfor %}

{% include paginator.html %}
