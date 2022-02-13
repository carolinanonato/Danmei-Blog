---
title: Danmei Blog
layout: "index.njk"
---

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Phasellus ac imperdiet magna. Nullam id dictum neque, in sollicitudin justo. Nam egestas eleifend eros, nec laoreet ipsum vehicula ac. Donec lectus augue, suscipit quis mattis at, pharetra at tortor. Aliquam luctus accumsan lectus, non faucibus dolor imperdiet sed. Praesent feugiat ultricies turpis ut malesuada. Ut gravida tellus et mi rhoncus, eu lobortis lorem ultrices.

Sed feugiat nulla dolor, sed facilisis nisl egestas non. Vestibulum ante ipsum primis in faucibus orci luctus et ultrices posuere cubilia curae; Sed vel velit leo. Mauris fermentum orci id ante sodales tempor. Aliquam eget risus ut nunc pellentesque tincidunt. Vestibulum elementum viverra tincidunt. Integer eu ultrices quam. In semper lorem id quam euismod consequat. Vestibulum at risus vitae nunc dignissim pharetra. Nulla id metus molestie, iaculis nibh sit amet, cursus nulla.

<ul class="list">
    {% for post in collections.posts %}
<li>
<a href="{{ post.url }}">
{{post.data.title}}

</a>
</li>
    {% endfor%}
</ul>