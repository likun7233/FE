

# 第18课 DOM修改添加
### 课程内容
#####1. 改变 HTML 内容
- innerHTML方法

		<html>
			<body>
			<p id="p1">Hello World!</p>
			<script>
				document.getElementById("p1").innerHTML="New text!";
			</script>
			</body>
		</html>


#####2. 改变样式
- element.style.xxx = xxx;

		document.getElementById("p2").style.color="blue";
		
		
#####3. 创建新的 HTML 元素
- 创建元素，然后把它追加到已有的元素上

		var para=document.createElement("p");
		var node=document.createTextNode("This is new.");
		para.appendChild(node);

		var element=document.getElementById("d1");
		element.appendChild(para);
		

#####4. 添加元素	
- appendChild
- insertBefore

#####5. 删除元素
- removeChild



#####6. 替换元素
- replaceChild

