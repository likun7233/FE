# 第15课 DOM方法



## 节点访问
#### 获取对应节点
1. document.getElementById

2. document.getElementByTagName

3. document.getElementByClassName

#### 获取邻居节点
1. node.nextElementSibling, node.previousElementSibling

#### 子节点
1. node.childNodes
包括所有节点，用nodeType == 1 判断是不是元素节点
2. node.children
node.children[0]获取第一个子节点
3. node.firstChild node.lastChild

#### 父节点
1. parentNode

## 节点类型
1. 用nodeType获取
2. 1：元素节点，2: 属性节点， 3: 文本节点
