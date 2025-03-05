---
title: Hello world
layout: default
author: Flisa Hedenhös
authors: ["Flisa", "Knota", "Urax"]
permalink: 
---

Hello world

Ett alias som jag använder brukar vara 
{{ page.author }}


<ul>

{% for author in page.authors %}

    <li>
        {{ author }}
    </li>

{% endfor %}

</ul>


En lista
- äpplen
- päron