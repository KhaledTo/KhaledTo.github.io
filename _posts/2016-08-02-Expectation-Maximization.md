---
layout:     post
title:      "Expectation Maximization"
date:       2016-08-02 17:00:00
author:     "Khaled"
header-img: "img/posts/jekyll-bg.jpg"
comments: true
---

## Test Katex
  
{% raw %}
<!-- The Normal Distribution -->
<div class="equation" data-expr="\displaystyle P(x)=\frac{1}{\sigma\sqrt{2\pi}}e^{-\frac{(x-\mu)^2}{2\sigma ^2}}"></div>
{% endraw %}


<script type="text/javascript">

    // grab all elements in DOM with the class 'equation'
    var tex = document.getElementsByClassName("equation");

    // for each element, render the expression attribute
    Array.prototype.forEach.call(tex, function(el) {
        katex.render(el.getAttribute("data-expr"), el);
    });

</script>