# 后端介绍

### 怼怼三国后端是基于nodejs运行采用TS语言开发的服务器

## 服务器种类

目前游戏按照功能拆分分为：

 [登陆服务\(loginserver\)](deng-lu-fu-wu-loginserver.md) 

[匹配服务\(matchserver\) ](pi-pei-fu-wu-matchserver.md)

[战斗服务\(raceserver\) ](zhan-dou-fu-wu-raceserver.md)

[榜单服务\(chartserver\) ](bang-dan-fu-wu-chartserver.md)

[游戏主要业务服务（cloudserver ps:一般称为gameserver\) ](zhu-ye-wu-cloudserver.md)

[数据落地服务（syncserver）](shu-ju-luo-di-fu-wu-syncserver.md)

## 数据库

游戏数据采用：

 redis承载热数据和mysql数据落地的模式  

redis开启持久化策略 

数据淘汰和落地依靠syncserver

