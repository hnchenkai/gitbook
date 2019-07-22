# 后端介绍

怼怼三国后端是基于nodejs运行采用TS语言开发的服务器，静态资源统一存储在Res目录下，游戏配置统一命名成config.json,启动的入口文件统一命名成app.js

## 服务器种类：

1. [登陆服务\(loginserver\)](deng-lu-fu-wu-loginserver.md) 
2. [匹配服务\(matchserver\) ](pi-pei-fu-wu-matchserver.md)
3. [战斗服务\(raceserver\) ](zhan-dou-fu-wu-raceserver.md)
4. [榜单服务\(chartserver\) ](bang-dan-fu-wu-chartserver.md)
5. [游戏主要业务服务（cloudserver ps:一般称为gameserver\) ](zhu-ye-wu-cloudserver.md)
6. [数据落地服务（syncserver）](shu-ju-luo-di-fu-wu-syncserver.md)

## 数据库：

1. redis承载热数据和mysql数据落地的模式  
2. redis开启持久化策略 
3. 数据淘汰和落地依靠syncserver的执行

 

