# Pycon2019成都站

## 类型推断，静态类型，JIT

语法树到语法树的函数 我们称之为**宏**。

类型大小本质为将类型看作一个集合，计算集合的大小（取值区间的大小）

学习路线：

Python的Virtual Machine

Stack Machine

[LLVM Based Machine](https://github.com/thautwarm/mapping-high-level-constructs-to-llvm-ir)

dis模块

[okmij.org](http://okmij.org/)

编译原理

Python字节码

## WEB API

**Web Application**是和用户直接交互的。

**Web API**返回纯数据格式的（如XML和JSON），与机器（如Web Application，iOS，Android等）进行交互。

RESTful API指符合REST规范的Web API，虽然几乎没有Web API完全符合REST规范。所以大概符合REST风格的现在都叫RESTful API。REST只是一个架构风格，而非强制要求。

Flask是一个开发Web API的工具，只提供最基本的功能，有良好的拓展性。选择Flask表示比起Djanro的方便你选择了灵活和更多的可控制性。因此比起`Flask+大而全的拓展`更推荐`Flask+一组优秀的工具`。

### 推荐的学习路线

1. 了解Web API设计原则
2. 学习Flask原生实现
3. 学习其他搭配工具

[李辉的个人网站 greyli.com](http://greyli.com/)

网站里有很多python web开发的教程和分享。

## NLP

* 任何时候都不要忘记“当初你想解决的问题”
* 把问题转化为具体统计问题或者能够使用机器学习解决的问题（不知道该怎么做时可以用EDA把握数据倾向）
* 根据你的时间和预算选择分析方法和合适的模型
* Just Python

## 其他

AWS 12要素应用宣言：无需猜测容量，摆脱无差异化工作等

AWS云基础设施，`Infrastructure is Code`，用面向对象的方式描述和构建基础设施。（上一代为`Infrastructure as Code`，用JSON等记录和描述基础设施）。