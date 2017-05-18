---
layout: page
title: Home
---

## Vítejte na stránkách o Susan Leigh Star

Susan Leigt Star (1954-2010) byla známou americkou socioložkou, která se specializovala na studium informací v moderní společnosti. Nejen o jejím životě, práci, dílech a oceněních se dočtete zde na našem webu.


## Příspěvky

Prohlédněte si vložené příspěvky:

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>

