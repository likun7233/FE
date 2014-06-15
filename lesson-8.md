# 第8课
2014-6-15 周日

## 课程目标

## 课程内容
##### 操作符
- 递增递减

#
    var a = 10;
    var c = ++a;
    var d = a++;
    var b = 'hello';    
    b += 'kevin';
   
- 非与或 ! && ||

#
    alert( !flase );
    alert( !0 );
    alert( !'');
    var a = true;
    alert( !a );
    alert( a && 1 == true); 
    alert(a || 1 == 0);
    
    // && 可用来判断是否存在
    $obj && $obj.on('click', fuction(){});
    
    function sum(val){
        reutrn ++val;
    }
    function sum2(val){
        val = val || 1; // || 可用与赋值
        reutrn ++val;
    }
    sum();
    sum2();

－ 乘*, 除法/, 求余%
    1. 对与*, 非number相乘会转换乘成number； '0.2'* 2;
    2. 转换失败 NaN
    



