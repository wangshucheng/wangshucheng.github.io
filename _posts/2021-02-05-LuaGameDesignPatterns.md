---
layout:     post
title:      LuaGameDesignPatterns
date:       2021-02-05
summary:    游戏设计模式——Lua实现
categories: DesignPatterns lua
---

https://github.com/wangshucheng/LuaGameDesignPatterns

## DesignPatterns

按照设计模式的功能进行划分，可以分为八类：
接口适配类，对象去耦类，对象创建类，抽象集合类，对象状态类，行为扩展类，算法封装类，性能与对象访问类。其中包含内容如下：
- 对象创建型：1.原型模式；2.工厂模式；3.抽象工厂模式；4.单例模式；5.生成器
- 接口适配型：1.适配器模式；2.桥接模式；3.外观模式
- 对象去耦型：1.中介者模式；2.观察者模式
- 抽象集合型：1.组合模式；2.迭代器模式
- 行为扩展型：1.访问者模式；2.装饰器模式；3.责任链模式
- 算法封装型：1.模版方法模式；2.策略模式；3.命令模式
- 性能与对象访问型：1.享元模式；2.代理模式
- 对象状态型：1.备忘录模式

[简述21种设计模式]: https://www.cnblogs.com/zhou--fei/p/10454244.html  
[各种设计模式的Unity3D C#版本实现 by 浅墨]: https://github.com/QianMo/Unity-Design-Pattern

## FrameworkPattern

- BehaviorTree 行为树
- ECS 实体组件系统
- FSM 有限状态机
- MessageDispatch 消息分发
- MessageQueue 消息队列
- MVC 
- MVVM 
- ObjectPool 对象池
- PureMVC 