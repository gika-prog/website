---
title: Search
permalink: /search/
layout: flow
jumbotron:
    title: Search
    inner_class: dotted
    description: ""
    image: /assets/images/content/96boards-home-image-2.jpg
description: |-
    Search the Linaro Website.
css_bundle: search
---
<script>
  (function() {
    var fess = document.createElement('script');
    fess.type = 'text/javascript';
    fess.async = true;
    // fess.src is URL for FSS JS
    fess.src = '/assets/js/vendor/fess-ss-11.4.min.js';
    fess.charset = 'utf-8';
    fess.setAttribute('id', 'fess-ss');
    fess.setAttribute('enable-order', 'true');
    fess.setAttribute('link-target', '\_blank');
    fess.setAttribute('enable-labels', 'true');
    // fess-url is URL for Fess Server
    fess.setAttribute('fess-url', 'https://search.linaro.org/json/');
    var s = document.getElementsByTagName('script')[0];
    s.parentNode.insertBefore(fess, s);
  })();
</script>

<fess:search></fess:search>
