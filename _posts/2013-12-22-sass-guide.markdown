---
layout: post               
title:  "sass 入门"
date:   2013-12-22 21:05:00
categories: design
---
sass 是一种基于css语法并在此基础上拓展得技术，最终回生成css文件
{% highlight  css%}
@mixin rundedradius($radius){
  border-radius: $radius;
  -moz-border-radius: $radius;
  -webkit-border-radius: $radius;
}
#box{
  @import rundedradius(10px);
  width: 320px;
  height: 240px;
}
{% endhighlight %}
