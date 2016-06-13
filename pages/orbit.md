---
layout: page
title: Orbit Example
permalink: /orbit/
gallery:
    - image_url: /assets/img/tree.jpg # url of image
      image_caption: Image of a tree # caption of image
      image_alt: Image of a tree # alt= description of image
    - image_url: /assets/img/ocean.jpg
      image_caption: Image of Ocean
      image_alt: Image of Ocean      
      
---

This is an example of a <a href="http://foundation.zurb.com/sites/docs/orbit.html">Foundation Orbit</a> slider.
To insert a slider into a page, one must add the following code to the header of the page you'd like the slider to appear on.


```
gallery:
    - image_url: /assets/img/tree.jpg # url of image
      image_caption: Image of a tree # caption of image
      image_alt: Image of a tree # alt= description of image 
```

This allows you to add each image element as well as caption and alt information. Then, add `{ % include orbit.html % }` (without the spaces between the `{` and `%`) where you'd like the Orbit slider to appear.


{% include orbit.html %}