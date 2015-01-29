---
layout: post
title:  "When to use Delegation, Notification, or Observation in iOS"
date:   2015-01-30 00:07:25
categories: iOS
tags: featured
image: /assets/article_images/andreasbg.png
---

*初学iOS编程，没仔细考虑就决定用Swift语言进行开发的确欠妥，不过事已至此，也不能给自己不学OC找借口，不管怎么说，自己就是菜鸟一枚，Android学了点皮毛就转战iOS了，希望今后能多写点东西，加深自己的印象并且更好地理解。*

开发中不可避免的需要在页面间传值。在Android开发中自己最常使用的是在`Intent`中传递值，当然这种情况是有页面跳转时用的，还有就是对应的`startActivityForResult`, 而平常存储少量简易数据时可使用`SharedPreference`的存取随时来进行访问。再来就是`BroadCast`和`Receiver`了。那么iOS呢？今天参阅了许多文章，以下大多摘自
[http://blog.shinetech.com/2011/06/14/delegation-notification-and-observation/](http://blog.shinetech.com/2011/06/14/delegation-notification-and-observation/)

iOS中的相关机制有以下三种:  
1. Delegation  
2. Notification Center  
3. Key Value Obesering  

首先介绍一下这三种机制是什么:

上述的三种机制都是两两对象不需要耦合而进行相互通信的方式, 即controller之间不需要相互依赖就能知道自己需要的消息、事件的发生。

##Delegation   
##Notification Center  
##Key Value Obesering 




#`To be continued...`


[jekyll]:      http://jekyllrb.com
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-help]: https://github.com/jekyll/jekyll-help
