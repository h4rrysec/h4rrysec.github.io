---
layout: default
---

# Welcome.

If your reading this it means you've stumbled across my mess of a blog. Congrats (and apologies).

I plan to use this for several different purposes, namely:
  - Documentation of projects I'm working on (or -want- to work on)
  - Opinons/ideas regaring a wide range of topics around cybersecurity and technology
  - Homelab planning, builds, testing
  - Digital privacy and everything that comes with it (yes, security and privacy are different... actually i'll write about that, good looks)
  - etc.

  Feel free to reach out at my email (harrisonstone1@protonmail.com), or else find all my other (semi) professional platforms here: https://harrison-stone.carrd.co/

## Thanks!

Harrison Stone (h4rrysec)

-------------------------------------------------------------

<h1>Recent Posts:</h1>

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a> - 
      <small>{{ post.date | date: "%B %-d, %Y" }}</small>
    </li>
  {% endfor %}
</ul>
