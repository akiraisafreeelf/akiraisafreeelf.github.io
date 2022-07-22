---
layout: 
title: 与Disco Diffusion的交涉
date: 2022-07-21 16:56:21
tags: DD跑图
---
DD跑图几天后，我感觉这事本质上和与人类沟通没有太大区别。
想好自己想要的东西，简单、明确、详尽地表达，并根据对方的反馈，分析双方理解偏差在哪里，进一步调整自己的字词/参数以确保双方逐渐逼近the same page，如此循环。

今天尝试时，发现AI没法依据文字叙述画出我想要的夸张巨大物，它无法理解我想要的比例和构图，当然也因为我无法用文字说清，只能表达一种朦胧的“感觉”。

我想要一只蓝鲸从城市中间穿过，这只鲸要巨大到连鳍都可以遮挡建筑物，而且整个城市要在深海。你可以从我的prompt里看出我的努力，也能从AI的反馈里看出它的努力，结果之所以会差那么远，我想最大的问题是底图。如果这种明显的城市景观要变成深海，对于AI来说可能还是太难，让我说清楚也够难的。

即使用母语来叙述，我相信也没有几个人能在这张图的基础上想像出我的想像。不论是面对一个活人或者一个AI，只有用图片本身交流，才可能让对方想像个大概。也就是，只有我自己先调色改图叠一层海水并且画出那只鲸的轮廓，才可能跑出完全合意的图。有一瞬间甚至想捡起素描自己画框架了……也许有一天真会这么做。

AI取代不了人，而人有了AI可以梦得更狂野。

----------  

### 今日跑图集合 ###

- 目标：探索垫底图时的AI表现，画深海城市+巨大物
- 结果：不大成功，但也有意外收获	

↓底图：朋友圈扒的莲塘随手拍
{% asset_img mmexport1658316581453.jpg This is an image %}  
#  
↓A beautiful painting of a silent city deep under the sea, with a huge blue whale swimming by, init scale 1000, skip steps 100  
是真的有被惊艳到，没想到AI会直接把云变成鲸鱼
{% asset_img TimeToDisco7.png This is an image %}  
#  
↓prompt同上，增加自由度init scale 1000, skip steps 50
{% asset_img TimeToDisco8.png This is an image %}   
#  
↓为了画出深海在prompt里加了sank，还是无效
{% asset_img TimeToDisco9.png This is an image %}  
#  
↓A beautiful painting of a huge blue whale, swimming through the middle of a flooded city and obscuring a bunch of buildings with its fin, init scale 10, skip steps 10  
提高自由度，增加表现鲸鱼之大的语句，把sank换成flooded，巨大物出现了，但还是没有深海
{% asset_img TimeToDisco10.png This is an image %}    
#  
↓A beautiful painting of a giant whale fin, swimming through the middle of a sunken city and obscuring a bunch of buildings  
想让画面只出现巨大的鱼鳍，把flooded改成sunken想画出深海城市，结果大翻车
{% asset_img TimeToDisco11.png This is an image %}    
#  
↓A beautiful painting of a giant whale, swimming across Atlantis and obscuring it with its fin, [1024 512]  
都祭出Atlantis了，改了画幅，还是没有深海T T 不过意外的是出现了冬天，我确实有想过画个白雪皑皑的深圳来着
{% asset_img TimeToDisco12.png This is an image %} 

----------

###近日其他（能看）跑图一览###

↓A cute portrait of young Doctor Strange, displaying his new magic by Kagaya Yutaka 能跑出这样的幼年奇异博士很惊喜了，DD并不适合画人
{% asset_img TimeToDisco(0)_2.png %} 
#  
↓A astonishing photo of a huge kestrel, hovering above a tumultuous sea at dawn by Kagaya Yutaka 虽然不是我要的红隼但很喜欢这张！猛禽的眼神，巨大物！
{% asset_img TimeToDisco(4)_2.png %} 
#  
↓A beautiful painting of a cute enormous kestrel, flying with the moon on its wings by Bob Ringwood *迭代步数500
{% asset_img TimeToDisco(5)_2.png %} 
#  
↓A beautiful painting of a cute enormous kestrel, flying with the moon on its wings by Bob Ringwood *迭代步数250
{% asset_img TimeToDisco(6)_0.png %} 