# 第4课
## 目标
  熟悉css样式加载方式，常见的选择器方式，框模型，定位
## CSS基础
### 样式分类
1. 默认样式，内联样式（标签内部style＝"color: red; font-size: 15px;"）,内部样式（head内<style></style>），
2. 外部样式<link rel="stylesheet" type="text/css" href="mystyle.css" />
3. 外部样式 @import url("mystle.css")， 放在写样式的地方

### 选择器
1. 标签选择器：a{}, h1{}, div{}
2. 类选择器（以.开始） .my-class{}
3. id选择器（以#开始） ＃my-id{}
4. 组选择器（选择多个，以,分割） .class1, .class2{}
5. 派生选择器具（选择孩子,以空格分割） .class1 h1{}
6. 组合选择器（选择类为class1的span元素） span.class1{}
7. 伪类选择器 a:hover, a:link{color: #ff7700}

### 典型样式
##### 1.背景
    background-color: #ff00ff;
    background: url('bg.png') 0 0 no-repeat;
    background-position: top center;
    background-size: 100px 100px;
    background-repeat: no-repeat;
    background-image: url('bg.png');

##### 2.文字
    text-align: left; //center, right
    text-decoration: none; // a链接常用
    color: red;
    font-family: serif, '微软雅黑';
    font-weight: normal; // bold
    font-size: 20px;
    font-style: normal; //正常，斜体
##### 3.边框
    border: 1px solid #ddd; //solid:实线，dotted虚线
    border-top: 1px solid;  //border-left border-bottom border-right
    border-radius: 10px 6px 3px 1px; //左上 右上 右下 左下
    10px = 10px 10px 10px 10px;
    10px 5px = 10px 5px 10px 5px;
    10px 5px 1px = 10px 5px 1px 5px;

### 框模型
1. 外边距，边框，内边距，内容
2. 边距的设定
3. 边距的合并

### 定位
1. 理解几种定位方式fixed absolute relative
2. 理解浮动

## 课后练习
1. 做个百度首页
2. 做个bbs页面，参考：http://phpbb3.pixelgoose.com/index.php?style=2
