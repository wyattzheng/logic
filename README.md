# 逻辑学

本仓库记录 `逻辑学` 相关的概念及理解。

# 基本概念

## 事物

是指客观存在的一切的可以被讨论的任何东西。

### 抽象对象

有一类对象，不在任何具体的时间或空间中存在，但可以从物理意义上真实存在的对象中抽象出来。

> 把几个事物的共同属性抽象出来，可以看作一个抽象事物。

> 柏拉图主义承认`抽象对象`的存在，包括数学对象`数量`、`结构` 都是存在的。

## 概念

`概念`是思维的基本单位，是我们脑子中的想法。

> 人对世界有一个`心智模型`, 心智模型是一种外部现实的内部符号或表示，假设在认知、推理和决策中起主要作用。肯尼斯·克雷克 (Kenneth Craik) 在 1943 年提出，大脑构建了现实的“小规模模型”，用于预测事件。

> 我们脑海中的世界形像只是一个模型。在他的头脑中，没有人想像整个世界、政府或国家。他只选择了概念和它们之间的关系，并用它们来表示真实的系统。

## 属性

`属性`是`事物`的特征。

> 特征就是可以用来与其它事物作区分的点

### 本质属性

`本质属性`是事物的有决定性意义的特有属性。即`决定`该事物之所以为该事物而不是别的事物的特有属性。

### 非本质属性

`非本质属性`是指一个事物或概念不具有决定性意义的属性。

> 举个例子，对于`猫`来说，它的非本质属性可能包括它的颜色、体型、年龄等。这些属性虽然可以描述猫的外观和特征，但它们并不决定`猫`这个事物可以与其它事物区分开。

## 内涵

`内涵`是指概念反映的事物的`本质属性`的总和。

## 外延

`外延`是具有概念反映的事物的`本质属性`的总和的所有对象的集合。

## 定义

`定义`是对`事物`或`概念`的内涵和外延的准确描述。

> 有意思的是，这是`定义`的`定义`。

> 我们平常常用`是`这个词，将某种陈述换了一种等价的说法, 其实是在进行`定义`。

## 集合

集合就是一堆`事物`形成的整体。

> 集合就是一堆东西，并且是集合论最基本的概念之一

> 若把集合看作“符合任意特定性质的一堆东西”，会得出所谓罗素悖论。为解决罗素悖论，数学家提出公理化集合论。在公理集合论中，集合是一个不加定义的概念。

> 集合的元素可以是任何事物，可以是人，可以是物，也可以是字母或数字等。

## 类

`类`是指具有相同属性的`事物`的`集合`。

> 举个例子, `猫是动物`, 实际上是在说 `猫` 是一种 `动物`。也就是`猫类`是`动物类`的一个子集。

> `是` 这个词除了下定义以外, 也常表达`是一种`的意思。

## 分类
    
`分类`是指将`事物`的`集合`按照其`属性`进行划分。

> 例如, `自然数集合 = {1, 2, 3, ...}`, 可以划分为 `{x|x是偶数}` 和 `{x|x是奇数}`, 也可以划分为 `{x|x是质数}` 和 `{x|x是合数}`

## 关系

关系是事物之间的相互的作用、相互的影响。

> 一个事物的变化会引起另一个事物的变化，这种相互的作用就是关系。
> 关系也是一种事物，也可以被分类。

## 符号

事物之间存在着某种指代或表述关系，如“X能够指代或表述Y”，那么事物X是事物Y的符号，Y是X指代的事物或表述的意义。

> `符号`可以用来指代`事物`或`概念`。

> `符号`具有简明性、统一性、方便性

> 人类的语言系统就是一种符号系统。人类所用的文字其实就是符号。

# 逻辑推理

## 命题

`命题`就是一个可以判断真假的陈述句。

> 由于这样的定义, 命题适用非常的广泛。例如, `今天是星期天` 就是一个命题。

> `命题`要么是`真`，要么是`假`，不可能既是`真`又是`假`（这是逻辑学的公理决定的）。

### 命题的分类

`命题`也可以被分类, 这里只列举了两种。

#### 全称肯定命题

`全称肯定命题`是指断定某个集合中的所有`事物`都具有某个属性的命题。

> 例如, `所有的人都会死` 就是一个`全称肯定命题`。

#### 特称肯定命题

`特称肯定命题`是指断定某个集合中的有`事物`具有某个属性的命题。

> 例如, `有些人会死` 就是一个`特称肯定命题`。

## 推理形式

推理形式是一种`抽象结构`，用于描述和分析推理的结构和有效性。它们是一种模式或规则，用于从前提到结论的合理推导过程。

> 推理形式不关心具体的内容，而是关注于推理的逻辑结构和形式正确性。在推理形式中，逻辑关系是基于形式逻辑规则而不是语义内容来确定的。

> 如果`推理形式`是有效的, 那么只要所有`前提`是真的, 结论必定是`真`的, 结论为`假`是不可能的

### 常见的有效的推理形式

- `假言推理`：如果 `P` 成立，那么 `Q` 成立。`P` 成立，所以 `Q` 成立。

- `假反推理`：如果 `P` 成立，那么 `Q` 成立。`P` 不成立，所以 `Q` 不成立。

- `假设加法`：`P` 成立，所以 `P` 或 `Q` 成立。

- `分离`: `P` 与 `Q` 都是真的。因此, `P` 是真的。

## 三段论

`三段论`是一种推理方法。

> 三段论是指由两个前提推出一个结论。两个前提分别是`大前提`和`小前提`。

> 三段论也可以是无效的，除非使用有效的推理形式。

## 形式逻辑

> 现实中的命题所对应的语句常常可以转换成对应的由符号构成的命题来讨论。

> 转换成符号讨论后更方便我们了解命题的逻辑结构。

> 使用逻辑运算符使得命题语句结构中的各个部分被分开, 逻辑结构则用规定的符号表示，而剩下的部分可能是指代了某种事物的符号。

### 逻辑运算符

`逻辑运算符`是用来把语句连接成更复杂的复杂语句。

> 逻辑运算符有`非`（¬）、`与`（∧）、`或`（∨）、`蕴含`（→）、`等价`（↔）。

> “非”是一个一元操作符，它只操作一项（¬ P）。剩下的是二元操作符，操作两项来组成复杂语句（P ∧ Q, P ∨ Q, P → Q, P ↔ Q）。

### 量化符号

1. `全称量词`：∀，表示“对于所有的”。
2. `特称量词`：∃，表示“存在”。

> 实际上这两个符号可以互相转换。

### 断言符号

对于某个`事物`，我们可以进行断言, 将这种断言记为: 
- 命题：`A(x)` 成立 , `x` 代表这个`事物`, `A` 代表这种`断言`。

### 例子

- `所有的人都是动物` 可以表示为 `∀x(人(x) → 动物(x))`

- `有些人是动物` 可以表示为 `∃x(人(x) ∧ 动物(x))`
