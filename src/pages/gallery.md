---
title: Gallery
altTitle: 'Our students in action'
layout: 'layouts/gallery.html'
permalink: '/gallery/index.html'
---


<img src="../_includes/images/camera.svg" class="camera-detail" alt="camera picture" />

<article class="gallery">
<!-- display all images using info in _data/images.json -->
{%- for img in images.images -%}
<figure class="image-block-{{loop.index}}">
   <img src="{{ img.localUrl }}" alt="{{ img.title }}" />
   <figcaption>
      {{ img.title }} &#127909; {{ img.student }}
   </figcaption>
</figure>
{%- endfor -%}
</article>