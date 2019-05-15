Task 03
==============
1.环境搭建
--------------
* 1)定义

  字典是另一种可变容器模型，且可存储任意类型对象。  
  字典的每个键值 key=>value 对用冒号 : 分割，每个键值对之间用逗号 , 分割，整个字典包括在花括号 {} 中

* 2)创建
```
  d = {key1 : value1, key2 : value2 }     
  dict = {'Alice': '2341', 'Beth': '9102', 'Cecil': '3258'} 
  dict1 = { 'abc': 456 }   
  dict2 = { 'abc': 123, 98.6: 37 }  
 
```

* 3)字典的方法  
a.访问字典里的值
```
dict = {'Name': 'Zara', 'Age': 7, 'Class': 'First'}
print "dict['Name']: ", dict['Name']
print "dict['Age']: ", dict['Age']

>>> dict['Name']:  Zara
>>> dict['Age']:  7
```
b.修改字典
```
dict = {'Name': 'Zara', 'Age': 7, 'Class': 'First'}
 
dict['Age'] = 8 # 更新
dict['School'] = "RUNOOB" # 添加
 
 
print "dict['Age']: ", dict['Age']
print "dict['School']: ", dict['School']

>>> dict['Age']:  8
>>> dict['School']:  RUNOOB
```
c.删除字典元素
```python
>>> d.pop('Bob')
75
>>> d
{'Michael': 95, 'Tracy': 85}
```
2.集合
----------------
* 1）特性  
1.不同元素组成   

2.无序   

3.集合中的元素必须是不可变类型  

* 2)创建
```
s = {1,2,3,4,5,6,7,8}
```

* 3)方法
1.add 向集合中添加元素  
```
>>> s = {1, 2, 3, 4, 5, 6}
>>> s.add("s")
>>> s
{1, 2, 3, 4, 5, 6, 's'}
```
2.clear 清空集合
```
>>> s = {1, 2, 3, 4, 5, 6}
>>> s.clear()
>>> s
set()
```
3.remove 删除集合中的一个元素（如果元素不存在，会引发 KeyError)
```
>>> s = {1, 2, 3, 4, 5, 6}
>>> s.remove(3)
>>> s
{1, 2, 4, 5, 6}
```

3.判断语句（要求掌握多条件判断）   
---------------- 
a.多条件
```
if 表达式1:
    语句
    if 表达式2:
        语句
    elif 表达式3:
        语句
    else
        语句
elif 表达式4:
    语句
else:
    语句
```
b.while循环
```
count = 0
while count < 5:
   print (count, " 小于 5")
   count = count + 1
else:
   print (count, " 大于或等于 5")
```
c.for循环
```
for i in range(5):
    print(i)
 ```
4.三目表达式
----------------
条件为真时的结果 if 判段的条件 else 条件为假时的结果 
```python
x =1
y =2
r = x if x > y else y
```




