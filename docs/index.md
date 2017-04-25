---
layout: default
---

# Welcome To The Project

We will use this site to host files from the 3D 360 videos shot during a Mercer JMS Media Entrepreneurship 2017 course.

<iframe width="560" height="315" src="https://www.youtube.com/embed/N3t-qLYSpxw" frameborder="0" allowfullscreen></iframe>
<br>
<iframe width="560" height="315" src="https://www.youtube.com/embed/govZ_bD3GhE" frameborder="0" allowfullscreen></iframe>
<br>
<iframe width="560" height="315" src="https://www.youtube.com/embed/NVUi94sYHQo" frameborder="0" allowfullscreen></iframe>
<br>
<iframe width="560" height="315" src="https://www.youtube.com/embed/UAxBUUTZjnY" frameborder="0" allowfullscreen></iframe>
<br>
*Below* are the design teams portfolios, click their names to learn more. *Above* to the upper right is the documentation for the various stages of project development. 

Lastly the **about** page describes the process for this site to be updated and maintained. 


<div class="home">
  <h1 class="page-heading">SME Information</h1>

  <ul class="post-list">
    {% for post in site.posts %}
      <li>
        <span class="post-meta">{{ post.date | date: "%b %-d, %Y" }}</span>

        <h2>
          <a class="post-link" href="{{ post.url | prepend: site.baseurl }}">{{ post.title | escape }}</a>
        </h2>
      </li>
    {% endfor %}
  </ul>

  <p class="rss-subscribe">subscribe <a href="{{ "/feed.xml" | prepend: site.baseurl }}">via RSS</a></p>
  <p class="post-date">Published: {{ 'now' | date: "%x %X" }} UTC</p>
</div>
