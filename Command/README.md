## 命令模式

### 概述
在开发中，我们经常需要向某些对象发送请求，但是并不知道请求的接收者是谁，也不知道被请求的操作是什么。我们希望做到只需在程序运行时指定具体的请求接收者即可，可以使用命令模式来进行设计，消除请求发送者与请求接收者彼此之间的耦合，让对象之间的调用关系更加灵活。

### 结构
![命令模式结构图.jpg](http://7u2eqw.com1.z0.glb.clouddn.com/命令模式结构图.jpg)

### 实现
使用一个音乐播放器的例子，有播放，暂停和停止播放三种命令。

### 总结与分析
命令模式的本质是对命令进行封装，将发出和执行命令的责任分割开。命令模式中的每一个命令都是一个操作，请求方发出请求，要求执行一个操作;接收的一方收到请求，并执行操作。