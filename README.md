# 环境与能源智慧管理平台（EIC）

## EIC软件定义

```
实现监控、分析、挖掘、管理之间协同工作，具有良好的自适应性、良好的可扩展性和免维护性的一套软件解决方案。
```

该软件运行于 **windows平台\(win7/win10 32位/64位兼容\)** 下，支持Chrome浏览器。

就地系统直接独立部署在现场，数据实现秒级传送；远程系统已多项目形式统一部署在云服务器，数据采集步长为5分钟，时间均由网关（采集软件）自由设定。

## 概要设计点

主要考虑点：

1. 《EIC数据管理平台》满足云端服务器需求同时也要适用于就地服务部署及应用，并考虑平台独立运行及可行性。

2. 后台基于DOM Framework多层架构，模块化、组件化、扩展性等设计实现。

3. 前端重构实现Chrome浏览器支持。

4. 兼容性问题，软件要求支持：IE 10，本设计所使用框架暂时不考虑IE浏览器需求，chrome测试为主。

## 概要设计产品目标参考图

![](/assets/数据任务管理.png)

