---
title: 2020云创云计算技能预选赛参赛体验续
categories:
  - 其它
tags:
  - 竞赛
  - 云计算
date: 2020-02-18 10:57:08
---

今天开开心心地跟老师讨论着项目文档,突然消息框一抖,我的受虐遭遇拉开了序幕.

有幸蹭得一次额外的平台接触机会,我接手时分数是负几千.掠过一眼题目后,心想,"这不就是第一天的题目么".我快速按第一天的策略部署了一遍,3个实例的负载均衡.看着分数涨了一会,就屁颠颠地跑去研究CDN服务了.CDN配完后看了下成绩,"尼玛,分数怎么跌得怎么厉害".得分记录一堆POST错误,试着访问了下url,发现确实无法访问了.看着成绩一点点跌下去,我愈发焦急.虽然远程桌面很卡,但我还是强行冷静地排了排错,实在想不出问题便看了下题目.发现多了服务多了宕机事件...

![sz](https://tva3.sinaimg.cn/large/007VBhb5gy1gc47ytyqwzj30m90eqjt1.jpg)

城里人真会玩,早上比赛开始前还在赛题url上挂支付宝收款码,企图收智商税.

没其它好办法,摸索了下用模板新建了十几个实例,挂负载均衡上,挂了的实例手动终止,手动新建新实例.就这样,我慢慢增加实例.随着分数和实例成正比增加,我愈发大胆,打算一口气开它10个实例.然而,至此我才发现,实例的上限是15个.

也许我应该在性能与成本中寻找平衡才对,也许是我真的太菜了,我最终还是没拿到什么好成绩.应该做负载均衡么,还是应该做内容分发,应该有办法让服务器自己终止宕机实例并新建实例的吧......

今天又被虐了,可我怎么莫名有点兴奋呢?难道...我开始有抖M倾向了...真令人害怕.