---
title:
description: A blog for crafty and card making related things
sidebar_option: sidebar
featured_image_path:
facebook_image_path:
---

<div class="blog-index">  
  {% assign post = site.posts.first %}
  {% assign content = post.content %}
  {% include post_detail.html %}
</div>