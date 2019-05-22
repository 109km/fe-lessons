# 百度首页第一练

首先，先介绍两个新的标签 `img` , `input`

先动手使用一下这两个标签：

```html
<html>
  <head>
    <title>img 和 input</title>
  </head>
  <body>
    <img src="https://www.baidu.com/img/bd_logo1.png" alt="">
    <input type="text">
    <button>百度一下</button>
  </body>
</html>
```

大家打开这里以后会发现，这3个标签站在同一行。

因为这3个标签的布局属性，也就是上一节里提到的`display`的值为`inline-block`。从名字上看既是`inline`也是`block`，所以这种类型的标签特点是自己不独占一行，但是可以设置自己的宽高。


现在我们通过以往所学的知识让这三个元素更像百度首页一点：

```html
<html>
  <head>
    <title>img 和 input</title>
    <style>
      .logo{
        text-align: center;
      }
      .search{
        text-align: center;
      }
    </style>
  </head>
  <body>
    <div class="logo">
      <img src="https://www.baidu.com/img/bd_logo1.png" alt="">
    </div>
    <div class="search">
      <input type="text">
      <button>百度一下</button>
    </div>
  </body>
</html>
```

通过一些简单的改动，我们发现从外观上跟百度首页更加相似了对不对？

## 练习

1. 通过css修改logo的大小
2. 通过css修改input和button的样式，阅读资料 [css背景](http://www.w3school.com.cn/css/css_background.asp) 和 [css边框](http://www.w3school.com.cn/css/css_border.asp)。（PS：按钮背景色的值为 `#38f`）