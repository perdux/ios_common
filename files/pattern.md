## 设计模式

参考 《Head First 设计模式》

### 策略模式（Strategy Pattern）

#### 1. 设计原则

* 找出应用中可能需要变化之处，把它们独立出来，不要和那些不需要变化的代码混在一起。
* 针对接口编程，而不是针对实现编程。
* `有一个`可能比`是一个`更好。 （多用组合，少用继承）


#### 2. 定义

**策略模式** 定义了算法族，分别封装起来，让他们之间可以互相替换，此模式让算法的变化独立于使用算法的客户。