---
title: 九九乘法表
date: 2014-04-03 14:24 UTC
tags: ruby
---

用[highlight.js](http://highlightjs.org/)把代码高亮给配置好了，那么就来show一下刚接触ruby时写的九九乘法表吧...我这个人真无聊~\(≧▽≦)/~

```ruby
1.upto(9) do |i|
  1.upto(i) do |j|
    print  "%-12s" % "#{j} X #{i} = #{j*i}"
  end
  puts ""
end
```


然后再改写成一行模式,我是有多无聊，多大的人了啊喂...

```ruby
1.upto(9){|i| 1.upto(i) {|j| print  "%-12s" % "#{j} X #{i} = #{j*i}"}; puts ""}
```




PS.今天申请了个域名，[ikoala.me](http://ikoala.me).是不是瞬间高大上了很多呢，哈哈！