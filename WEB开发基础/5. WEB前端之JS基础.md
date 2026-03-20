# JavaScript简介
- ### 定义
  - #### JavaScript (简称"JS") 是一种具有函数优先的轻量级，解释型或即时编译型的编程语言
- ### 组成
  - #### 前端分层
    - ##### HTML 结构层
      - ###### 利用语义化标签搭建网页
    - ##### CSS 样式层
      - ###### 利用样式进行美化网页, 进行网页布局
    - ##### JavaScript 行为层
      - ###### 可以给网页添加动态效果
  - #### JavaScript分层
    - ##### ECMAScript
      - ###### 它是欧洲计算机协会, 大概每年六月中旬定制语法规范
    - ##### DOM
      - ###### document object Model, 即文档对象模型
    - ##### BOM
      - ###### browser object model, 即浏览器对象模型
- ### 语法
- ### 内置函数
  - #### alert
    - ##### 警告框
```html
<script type="textjavascript">
  alert("1");
</script>
```
- ### DOM
  - #### 节点树
    - ##### 节点即为标签, 树即为关系
  - #### 引用类型属性
    - ##### console.log(document);
    - ##### console.log(typeof document);
  - #### 常用属性
    - ##### documentElement: 获取到节点树的heml标签
      - ###### console.log(document.documentElement);
    - ##### head: 获取到节点树的head标签
      - ###### console.log(document.head);
    - ##### title: 获取到节点title标签的文本
      - ###### console.log(document.title);
    - ##### body: 获取到节点body
      - ###### console.log(document.body);
  - #### 方法
    - ##### getElementById: 它是DOM对象方法, 可以通过标签ID, 在JS当中获取标签
      - ###### 
                var element = document.getElementById("box");
                console.log(element);
                console.log(typeof element);
---
# jQuery框架
- ### 引包
  - #### 注意事项
    - ##### JS这门脚本语言需要嵌套静态网页中才可以执行的, 独立JS文件 [书写JS语法] 不能单独运行
  - #### 语法
```html
<script type="text/javascript" src="./jQuery.js"></script>
```
- ### 体验
  - #### 概述
    - ##### jQuery框架, 即函数库
  - #### 语法
```html
<html>
<head>
  ...
  <script type="text/javascript" src="./JS/jQuery.min.js"></script>
</head>
<body>
  <ul>
    <li>1</li>
    <li>12</li>
    <li>123</li>
    <li>1234</li>
    <li>12345</li>
    <li>123456</li>
  </ul>
</body>
</html>
<script type="text/javascript">
  $("li").click(function(){
    $(this).css({'background': "red"});
  });
</script>
```
