# 4.2 概念原理

## 模块化

### 模块的概念

#### 广义

* 功能模块
    * 子系统
    * 单一功能的模块

##### 狭义

* 程序模块

## 此处有图片

## 抽象，逐步成精


问题定义---->编码

粗略方案---->详尽方案

## 抽象类型

* 过程抽象
    **把完成特定的功能的指定序列抽象为一个过程**

* 数据抽象
    **把一组相似的数据对象抽象成一个数据类型**
    
    
    
## 信息隐避&局部化

* 信息隐避
    * 公有
    * 私有
    * 保护

* 局部化
    * 少用全局变量！


## 模块独立性

> 函数的独立性

* 不可在分的单一功能
* 接口简单（信息交换对简单的！）

### 关键词

#### 内聚

一个模块内部，哥哥元素彼此结合的紧密程度

##### 偶然内聚

##### 逻辑内聚

##### 时间内聚

##### 过程内聚

##### 通信内聚

##### 顺序内聚

#### 耦合

多个模块的关联程度，相互依赖的程度

##### 此处要有函数模块图

##### 非直接耦合

##### 数据耦合

##### 标记耦合

##### 控制耦合

##### 外部耦合

一组模块都访问了同一个全局简单变量

##### 公共耦合
一组模块都访问了同一个公共数据环境（全局数据结构or同一个文件or共享的一个通信区，内存中的同一个覆盖区）

##### 内容耦合


> 尽量
> 使用非直接耦合，数据耦合，
> 减少标记耦合，控制耦合，
> 限制外部耦合，公共耦合，
> 杜绝内容耦合




