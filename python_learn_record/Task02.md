Task 02
==============
1. 列表
--------------
* 1)标志

  列表的标志符号是“[]”

* 2)基本操作(创建，append(),pop(),del(),拷贝)

  A.append  
  
  方法append()将元素添加到列表末尾，而不影响列表中的其他所有元素。  
  
  motorcycles.append('ducati') 
  
  B.pop  
  
  方法pop()可删除列表末尾的元素，并能够接着使用它。并可使用pop()删除列表中任何位置的元素，只需在括号中指定要删除的元素的索引可。  
  
  popped_motorcycle = motorcycles.pop()  
  print(motorcycles)  
  print(popped_motorcycle)  
  
  C.del  
  
  如果知道要删除元素在列表中的位置，可使用del语句  
  
  del motorcycles[0]
  
  D.拷贝  
  
  判断深浅拷贝的方法：  
  ***直接等号赋值是浅拷贝(同时改变)，使用[:]就是深拷贝了（分别改变）***   
  
  示例：  
  ##浅拷贝
  A = [1,2,3,4,5]
  B = A
  
  ##深拷贝
  A = [1,2,3,4,5]
  B = A(:)
  
  总结：  
  1、浅拷贝只能拷贝最外层，修改内层则原列表和新列表都会变化。  

  2、深拷贝是指将原列表完全克隆一份新的。  
 


* 3)列表相关方法

2.元组
----------------
* 1）标志

  print('Hello, the first day of learning python!')
  
  name = input()  
  print(name)
  
  * 1）标志
  
  
  
  
  * 2)基本操作(创建及不可变性)
  
3.string字符串
----------------




1. 列表
1)标志
2)基本操作(创建，append(),pop(),del(),拷贝)
3)列表相关方法
2.元组
1)标志
2)基本操作(创建及不可变性)
3.string字符串
1)定义及基本操作(+，*，读取方式)
2)字符串相关方法
4.字符串格式化问题
