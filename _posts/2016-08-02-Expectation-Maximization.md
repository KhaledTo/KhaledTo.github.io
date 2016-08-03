---
layout:     post
title:      "Yet Another Jekyll Blog"
subtitle:   "The Birth of yet another jekyll blog, which would probably be soon lost in oblivion."
date:       2016-03-27 17:00:00
author:     "Shikher Verma"
header-img: "img/posts/jekyll-bg.jpg"
comments: true
tags: CodeMonkey
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