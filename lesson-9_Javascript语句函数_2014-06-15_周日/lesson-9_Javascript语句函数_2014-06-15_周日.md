# 第9课 JavaScript语句、函数
## 课程目标
  熟练使用语句，熟悉函数的使用，arguments
## 课程内容
#### 语句
##### 1. if语句
    var a = 100;
    if(a > 90){
      console.log('优秀');
    }else if(a > 60){
      console.log('良好');
    }else{
      console.log('不及格');
    }
    
##### 2. do-while
    var i = 0;
    do{
        i += 2;
    }while(i < 10);
    console.log(i);
    
##### 3. while
    var i = 0;
    while (i < 10) {
        i += 2;
    }
    console.log(i);
    
##### 4. for
    var len = 10;
    for (var i = 0; i < len; i++){
        console.log(i);
    }
    
##### 5. for-in
    var man = {
        'name': 'kevin',
        'sex': 'man'
    }
    for(var key in man){
        console.log(man[key]);
    }
    
##### 6. break、continue
    var i = 0;
    for(i = 0; i < 10; i++){
        if(i == 5){
            break;
        }
        console.log(i);
    }
    
    var j = 0;
    for(j = 0; j < 10; j++){
        if(j == 5){
            continue;
        }
        console.log(j);
    }

##### 7. switch
    switch(a){
        case 1: 
            //todo...
            break;
        case 2:
            //todo...
            break;
        default:
            //todo
    }
    
    var score = 70;
    if(score >= 90){
        console.log('优');
    }else if(score >= 70){
        console.log('良');
    }else if(score >= 60){
        console.log('中');
    }else{
        console.log('差');
    }
    
    switch(true){
        case score >= 90:
            console.log('优');
            break;
        case score >= 70:
            console.log('良');
            break;
        default:
            console.log('差');
    }
    

#### 函数 
1. 以function定义

#   
    /*****************/
    function sayHi (name, msg) {
        alert("Hello " + name + "," + msg);
    }
    sayHi("keivn", "this is msg");
    
    /*****************/
    function sum (num1, num2) {
        console.log(num1 + num2);
        return num1 + num2;
        console.log(num2); //return后不在执行
    }
    sum(10, 20);  
    
2. 理解参数
    - 数组 ［］
    - arguments为参数数组

# 
    function sum(){
        console.log(arguments);
    }
    sum(1);
    sum(1, 2, 3);
    
    /*无传统意义的重载*/
    function sum(a, b){
        return a + b;
    }
    function sum(a, b, c){
        return a + b + c;
    }
    sum(1, 2); //出错
    sum(1, 2, 3);
    
    
    /*用arguemnts实现重载*/
    function newSum(){
        var sum = 0;
        for(var i = 0; i< arguments.length; i++){
            sum += arguments[i];
        }
        return sum;
    }
    
    
    





