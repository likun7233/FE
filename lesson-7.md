# 第7课 Javascript基础

## 课程目标
认识javscript，掌握javascript的引入方式，熟悉基本数据类型，常量变量，掌握基本运算符的使用

## 课程内容

##### 1.认识Javascript
- javascript !== java
- 是客户端脚本语言
- ECMAScript, DOM, BOM（了解） 
- ![Alt ](http://g.hiphotos.baidu.com/baike/h%3D120/sign=74dff509728da977512f82298051f872/730e0cf3d7ca7bcb3409f115bf096b63f624a89d.jpg)

##### 2.Javascript引入方式
- \<script>开始,遇到\</script>结束
- \<script type="text/javascript" src="1.js">\</script>
- 标签的位置，放在body内的最下位置。区别css位置
- defer:脚本延迟到文档解析和显示后执行，对外部有效，有顺序（了解）
- async:不保证顺序（了解）

##### 3.Javascript语法
- 区分大小写
- 以$/字母/_开头，其他字符可以是数字
- 驼峰命名
- 注释
- 以；作为语句结束，代码块用{}
- 变量的定义，var a = 1, b = 2;
- 局部变量和全局变量

##### 4.数据类型
- typeof 查看数据类型
- undefined bollean string number object function
- undefined: 声明未初始化
- null: 空对象 
- number: 数字

######    
    var a = 1,
        b = 0.1,
        c = .2,
        e = 0.3,
    console.log( c + e == 0.5) //相等吗
    console.log( b + c == 0.3 ) //相等吗
