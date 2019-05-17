Task 04
==============
1.函数关键字
--------------

python中一共含有32个关键字：
'false', 'none', 'true', 'and', 'as', 'assert',   
'break', 'class', 'continue', 'def', 'del', 'elif', 'else',   
 'except', 'finally', 'for', 'from', 'global', 'if', 'import',   
 'in', 'is', 'lambda', 'nonlocal', 'not', 'or', 'pass', 'raise',  
 'return', 'try', 'while', 'with', 'yield'

　　--关键字-是Python内置的、具有特殊意义的表示符    
　　--使用时关键字后面不需要括号    



2.函数的定义
--------------


  你可以定义一个由自己想要功能的函数，以下是简单的规则：

    函数代码块以 def 关键词开头，后接函数标识符名称和圆括号()。
    任何传入参数和自变量必须放在圆括号中间。圆括号之间可以用于定义参数。
    函数的第一行语句可以选择性地使用文档字符串—用于存放函数说明。
    函数内容以冒号起始，并且缩进。
    return [表达式] 结束函数，选择性地返回一个值给调用方。不带表达式的return相当于返回 None。


```

def functionname( parameters ):    
   #"函数_文档字符串"     
   function_suite   
   return [expression]      
```


3.函数参数与作用域
--------------

   以下是调用函数时可使用的正式参数类型：

    必备参数
    关键字参数
    默认参数
    不定长参数


a. 必备参数    

必备参数须以正确的顺序传入函数。调用时的数量必须和声明时的一样。  

调用printme()函数，你必须传入一个参数，不然会出现语法错误：  

```

#可写函数说明
def printme( str ):
   "打印任何传入的字符串"
   print str;
   return;
 
#调用printme函数
printme();
```

b. 关键字参数

关键字参数和函数调用关系紧密，函数调用使用关键字参数来确定传入的参数值。

使用关键字参数允许函数调用时参数的顺序与声明时不一致，因为 Python 解释器能够用参数名匹配参数值。

以下实例在函数 printme() 调用时使用参数名：

```
  #可写函数说明
def printme( str ):
   "打印任何传入的字符串"
   print str;
   return;
 
#调用printme函数
printme( str = "My string");
```




4.函数返回值
--------------



5.File
--------------
* 1）打开文件方式（读写两种方式）

* 2）文件对象的操作方法

* 3）学习对Excel及CSV文件进行操作6


5.Os模块
--------------


5.Datetime模块
--------------
