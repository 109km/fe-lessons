# Exercise 04 : css更多功能

下面这两点一定要谨记：

* html核心思想：代表网页内容和结构。
* css核心思想：代表网页的外观。

通常编写一个html网页的顺序是：先结构和内容，然后再添加外观。这个顺序跟画画是很相似的，画画也是先画好轮廓、结构，最后再上色。

接下来我们学习更多的css知识。

每个html标签都可以加上自己的样式，但是这些样式有不同的种类，主要可以分为以下两类：

* 布局型：会改变html标签的占用空间的方式或大小。
* 自身样式型：仅改变自己的背景颜色，字体颜色等等。

下面看一个例子：

```html
<html>
<head>
  <title>了解更多的css</title>
  <style>
    .one{
       background-color: antiquewhite;
       color:red;
       height: 100px;
    }
    .two{
      background-color: rgb(119, 141, 143);
      color:#000;
      height: 200px;
      width: 400px;
    }
    .red{
      color:darkorange; 
      font-weight:bold;
    }
    .three{
      background-color:beige;
    }
  </style>
</head>
<body>
  <div class="one">
    <p>独占一行</p>
    <span>没有</span>
    <span>独占一行</span>
  </div>
  <div class="two">
    I'm number two <span class="red">!</span>
  </div>
  <span class="three">
    第三行
  </span>
</body>

</html>
```

我们观察一下上面的代码和实际看到的网页的样子，我们是不是发现有的标签霸占了一整行，但是有的却没有。

霸占一整行的标签有：`div` `p` ，没有霸占一整行的标签有 `span`。这就是不同的标签会带有自己默认的样式，有些标签的布局类型是独占一行，有些标签的布局类型是不占一行。

让大家感到困惑的可能是 `two` 这个标签，从外观上来看它并没有占满一整行，但是 `three` 这个标签本身是不独占一行的，但是却没有跟`two`在同一行。这个问题可以这么理解：独占一行的元素特点是不论自己要用多少，它都独占这一整行的空间。打个比方，假设我有100亩地，我用多少亩来种地是我的事情，但是这100亩地总归是我的，变不成别人的。

## 练习

1. 阅读这篇资料 [CSS display 属性](http://www.w3school.com.cn/cssref/pr_class_display.asp) ，然后尝试把自己的工作计划修改为只使用 `div` 这个标签，通过`class`来区分不同的功能。（提示：独占一行的元素是block元素，不独占一行且不能设置宽高的是inline元素。注意查看资料里的**TIY 实例**的部分）