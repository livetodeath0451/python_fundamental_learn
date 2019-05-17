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
c. 默认参数

调用函数时，默认参数的值如果没有传入，则被认为是默认值。下例会打印默认的age，如果age没有被传入：


```
#可写函数说明
def printinfo( name, age = 35 ):
   "打印任何传入的字符串"
   print "Name: ", name;
   print "Age ", age;
   return;
 
#调用printinfo函数
printinfo( age=50, name="miki" );
printinfo( name="miki" );


```
d. 不定长参数

你可能需要一个函数能处理比当初声明时更多的参数。这些参数叫做不定长参数，和上述2种参数不同，声明时不会命名。基本语法如下：

```
# 可写函数说明
def printinfo( arg1, *vartuple ):
   "打印任何传入的参数"
   print "输出: "
   print arg1
   for var in vartuple:
      print var
   return;
 
# 调用printinfo 函数
printinfo( 10 );
printinfo( 70, 60, 50 );
```


4.函数返回值
-----


a. 指定返回值与隐含返回值

 

    函数体中 return 语句有指定返回值时返回的就是其值

    函数体中没有 return 语句时，函数运行结束会隐含返回一个 None 作为返回值，类型是 NoneType，与 return 、return None 等效，都是返回 None。
---------

b. 语句位置与多条 return 语句

 

    python 函数使用 return 语句返回 "返回值"，可以将其赋给其它变量作其它的用处

    所有函数都有返回值，如果没有 return 语句，会隐式地调用 return None 作为返回值

    一个函数可以存在多条 return 语句，但只有一条可以被执行，如果没有一条 reutrn 语句被执行，同样会隐式调用 return None 作为返回值

    如果有必要，可以显式调用 return None 明确返回一个None(空值对象)作为返回值，可以简写为 return，不过 python 中懒惰即美德，所以一般能不写就不写

    如果函数执行了 return 语句，函数会立刻返回，结束调用，return 之后的其它语句都不会被执行了




5.File
--------------
* 1）打开文件方式（读写两种方式）

在python中，打开文件的命令为
```
open(file[,mode[,buffer]])
```

关于mode，有以下注意点：
```
r 只读方式打开，文件必须存在
w 只写方式打开，文件不存在创建文件，文件存在则清空文件内容
a 追加方式打开， 文件不存在创建文件
r+/w+  读写方式打开
a+追加和读写方式打开
rb  wb ab  rb+   wb+  ab+ 二进制方式打开
```

* 2）文件对象的操作方法

  相关方法详情见[Datetime模块](https://www.cnblogs.com/panwenbin-logs/p/5521358.html/ "悬停显示")  

* 3）学习对Excel及CSV文件进行操作6




6.Os模块
--------------
  
  
  相关方法详情见[Os模块](https://www.cnblogs.com/yufeihlf/p/6179547.html/ "悬停显示")  



7.Datetime模块
--------------
  
  
  
  相关方法详情见[Datetime模块](https://www.cnblogs.com/tkqasn/p/6001134.html/ "悬停显示")  

