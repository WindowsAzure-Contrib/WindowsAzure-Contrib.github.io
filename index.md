---
layout: index
title: Windows Azure Contrib
tagline: Community contributions for Windows Azure
---
{% include JB/setup %}


This GitHub organisation aims to bring together a collection of [Open Source Software projects](https://github.com/orgs/WindowsAzure-Contrib) related to Microsoft Windows Azure.

The organisation is guided by a [small team](https://github.com/orgs/WindowsAzure-Contrib/teams/owners) of open source contributors.

[View on GitHub](https://github.com/WindowsAzure-Contrib/)

[Follow on Twitter](https://twitter.com/azurecontrib)

---



<div class="row">
  <div class="span4">
    <h2>Contrib Projects</h2>
    <p>View the projects under the contrib organisation.</p>
    <p><a class="btn" href="https://github.com/WindowsAzure-Contrib">View projects &raquo;</a></p>
  </div>
  <div class="span4">
    <h2>Wider community projects</h2>
    <p>As well as the projects hosted here, there are a number of projects available in the wider community.</p>
    <p><a class="btn" href="/wider-community.html">View projects &raquo;</a></p>
  </div>
  <div class="span4">
    <h2>Microsoft Projects</h2>
    <p>The open source projects funded by Microsoft are also on GitHub</p>
    <p><a class="btn" href="https://github.com/WindowsAzure">View projects &raquo;</a></p>
 </div>
</div>

---

## Updates

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>


