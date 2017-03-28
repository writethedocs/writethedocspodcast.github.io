---
title: Recommended Podcasts
permalink: /recommended-podcasts/
---

Here are some other recommended podcasts:


{% for item in site.data.recommended_podcasts.podcasts %}

<a href="{{item.url}}"><img class="recommendedPodcasts" src="/assets/img/podcastthumbs/{{item.img}}" alt="{{item.title}}"/></a>

{% endfor %}


<div style="clear: both;"></div>

If you have a podcast you'd like to recommend, [let us know](/contact/) and we'll add it here.
