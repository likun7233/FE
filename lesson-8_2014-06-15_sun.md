# 第8课
## 课程目标
    掌握操作符的使用
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

- 乘*, 除法/, 求余%
    1. 对与乘除减, 非number相乘会转换乘成number；如果转换失败返还NaN

#
    var a = 10,
        b = "2",
        c = true,
        d = "hello";
    alert(a - b);
    alert(a / b);
    alert(a * c);
    alert(b % a);
    alert( a - c);
    
- 加+
    1. 对于加，任何与字符串相加会转换成字符串，再加

#
    var a = 10,
        b = "2",
        c = true,
        d = false,
        e = null,
        f = 'hello';
    console.log( a + a );
    console.log( a + b );
    console.log( a + c );
    console.log( d + c );
    console.log( e + f );
    console.log( a + f );
    console.log( f + (a + a) );

- 关系> <
    1. 如果都是number， 直接比较
    2. 如果都是string, 直接比较
    3. 如果一个是number，把另一个转换为number，比较

#
    2 > 1; //true
    "b" > "abc" //true
    "23" < 3 //false
    NaN < 3 // false
    NaN >= 3 // false
    "a" > 3 //fasle
    "a" <= 3 //false

- 等号== 和!=, 全等=== 和!==, 区别于赋值=

# 
    11 == "11" //true
    11 === "11" //false
    true == 1  //true
    true == 2 //false
    false == 0 //true
    NaN == NaN // false
    NaN != NaN //true
    undefined == 0 //true
    null == 0 //true;

- 条件操作符

#
    var num1 = 2,
        num2 = 1;
    var max = (num1 > num2 ) ? num1: num2;

- 赋值操作符

#
    var num = 10;
    num = num + 10;
    num += 10;
    num = num - 2;
    num -= 2;
    num %= 3;
    
     


