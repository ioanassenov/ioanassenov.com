---
layout: default
title: "Ioan - Experiences"
permalink: /experiences/
---

# Projects & Experiences

<div class="grid">
    {% assign items = site.experiences | sort: "date" | reverse %}
    {% for item in items %}
        {% include card.html
            title=item.title
            summary=item.summary
            link=item.url
            img=item.hero
        %}
    {% endfor %}
</div>