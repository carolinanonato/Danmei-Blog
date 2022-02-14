---
title: Danmei Reviews
layout: "index.njk"
---

<div class="info">My name is Carolina and this is my blog with danmei-related media reviews. If you’re new here you might be thinking “What does that word even mean?” Danmei (in Chinese: 耽美, translating to 'indulging beauty') is a genre of any type of media which features romantic relationship between male characters. In recent years danmei achieved widespread popularity, with web novels being adapted to donghuas, manhwas and tv shows, like The Untamed and Guardian. 

I’m an avid reader who, despite the novels having more than 2k pages each, try to read at least one or two per month. If I like it enough, I’ll definitely watch the donghua, try to follow the beautiful illustrations in manhwas and keep hoping for tv adaptations, even knowing China's censorship will take a big chunk of the original story. I hope my reviews convey some of this amazing and exciting world! </div>


<ul class="list">
&#11088; Here are my favorites &#11088;

    {% for post in collections.posts %}
<li>
<a href="{{ post.url }}">
{{post.data.title}}

</a>
</li>
    {% endfor%}
</ul>