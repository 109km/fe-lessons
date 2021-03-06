# JavaScript入门

## 目的

在`Javascript历史`一节里，我们提到了JavaScript这门语言设计最初的目的是为了提高表单验证效率，但是随着发展，这门语言的作用已经不仅限于表单验证了，而是用于实现用户与网页之间的交互。

为了满足上面这个需求，所以完整的JavaScript按功能的不同划分成了三个部分。

## 功能划分

DOM(Document Object Model)：用通俗的语言来解释就是用JavaScript中操作HTML的功能。

BOM（Browser Object Model）：用通俗的语言解释就是用JavaScript语言操作浏览器的功能。

ECMAScript（语言标准）：就是规定所有的浏览器厂商都需要按照同样的标准来实现JavaScript这门语言：相同的语法，实现了语言本身拥有的功能。因此写代码的时候，只需要写一遍，就可以在所有浏览器上运行。

举个简单的例子，我们把ECMAScript想象成一种语言的标准，比如定义了语法、句法、词法等等。DOM和BOM分别是两个管家，DOM是负责管理HTML文档的，BOM是负责管理浏览器的。单独看的话，我们会发现这三部分之间没有太多关联。

但是如果放在浏览器环境下，我们可以想象一下：ECMAScript完成自己的计算功能，在某些时刻可以与HTML或者浏览器进行沟通，这样它们就形成了一个有机整体。

## 语法

语法就是人（程序员）与计算机用某种语言沟通的时候，必须遵循的语言法则。就像英语有英语语法，中文有中文语法一样。

总体来说语法分为两种类型：

* 赋值型
* 操作型

赋值型的作用就是给 **变量** 赋值，变量是计算机世界里一个重要的名词，它的作用就是储存，用来储存数据用的，我们可以把变量想象成一个有名字的箱子。下面举个例子：

```javascript
var word = 'Hello';
```
上面这个例子里 `var` 的作用就是告诉计算机：我要创建一个变量，这个变量的名字叫`word`，然后 `=` 为赋值符号，右边是要放入这个变量的数据`Hello`。所以用白话描述一下上面这段代码的意思就是：把`Hello`这个词放入一个叫`word`的变量。

操作型的作用就是让计算机帮我们完成某种任务，更像我们在指挥计算机。看看下面这个例子：

```javascript
alert("Hello!");
```
这段代码的意思是：让计算机弹出一个弹窗，弹窗里的内容是`Hello!`。

接下来我们去探索一下更详细的语法世界。

### 基础数据类型

* String 字符串
* Number 数字
* Boolean
* Undefined

为什么数据需要类型？用现实生活里的例子来比喻的话，我想一定不会有人把袜子放到碗里吧？因为袜子的类型是*衣物*，而碗是用来盛放*食物*的器皿。

用计算机的例子来解释：我们知道 `1+1`可以进行计算，但是如果 `1 + Hello`是什么呢？

所以确定了数据的类型之后，我们才会根据不同的数据类型确定可以执行的操作。




### 函数

### 控制语句

### 循环语句




## DOM


## BOM
