# Day01+绪论、Python基本语法、线性代数(上)

#### 1.今日所学内容梳理：（可以是思维导图、也可以是文字、音频、视频等）&#x20;

今天学习了Python环境的配置，以及对于Python基础语法的概览

#### 2.今日学习后的感想：（记录自己最真实的感想感受即可，如学会了的喜悦与充实、未能解决困难的苦恼等）&#x20;

基础的定义与概念对于后期的学习非常重要

#### 3.尝试努力解决后仍未解决的困惑：（比如哪个重要知识点还没搞懂、有个具体的问题需要大家帮助解答等）&#x20;

今日无未解决的困惑

#### 【今日练习作业】

*   题目1（数据类型）

列表属于（A）类型，元组属于（A）类型，字典属于（B）类型。

    A. 序列 B. 映射*    

集合内的元素是否可以重复？B

    A. 可以 B. 不可以*

题目2（变量）

判断以下变量命名是否合法，如不合法，请说明原因：

    A.\_boy B.4student C.class D.first number

    除A外均不合法

*   请将1，2，3，4，5打包赋值给变量a,b,c,d,e

````python
a,b,c,d,e = 1,2,3,4,5

```*

   请分别用下划线命名方式和驼峰体命名方式命名一个变量

```python
xia_hua_xian = 1 #下划线命名
TuoFengTi = 2 #驼峰体命名
```*

   题目3（控制语句）*    

   分别简述for循环、while循环和if分支语句的执行过程

    for循环遍历可迭代对象；

    while循环当条件为真时执行循环，否则跳出循环；

    if语句，当判断条件为真时执行语句，否则执行下一步语句*

   题目4（输入输出）*    

   用input语句分别输入两个数字，并实现两个数字的相乘。

    ```python
    x1 = input("输入第一个：")
    x2 = input("输入第二个：")
    print("乘积为：", int(x1)*int(x2))
    ```

    *   用format分别实现黄金分割比值0.6180339887 保留前3位的浮点数输出以及保留1位小数的百分比输出。

    ```python
    GoldenRatio = 0.6180339887
    print("{0:.3f}".format(GoldenRatio)) # 保留前3位的浮点数

    print("{0:.1%}".format(GoldenRatio)) # 保留1位小数的百分比输出
    ```*    

   将下列X处的代码补全，实现如图所示的格式化输出。

![](https://dme66dguw1.feishu.cn/space/api/box/stream/download/asynccode/?code=ZmRlN2JmNjk3ZjYxY2Q1OWU2NDViNjcyOGYzMDBmOThfQllMSVR0dEVoUFJHUDZwcVNsbVBhbUFQNE96c2RDZXRfVG9rZW46Ym94Y25tUU45MEJwOENQaHlCbThYNzN5OVJkXzE2NTU5NTIwODM6MTY1NTk1NTY4M19WNA)

for i in \[0,1,2,3,4,5]:

print("X1".format("X2"*(2*i+1)))

```python
for i in [0,1,2,3,4,5]:
    print("{0:-^20}".format("*" *(2*i+1)))
````

*   题目5（程序格式）

以下格式是否符合PEP8的格式建议，如不符合，请予以修改。

A x=10

```python
x *= 10
```

B y = (3-1)/8

```python
y = (3 - 1) / 8
```

C t = (1,2,3,4,5)

```python
t = (1, 2, 3, 4, 5)
```

D x = 10

```python
x = 10
```

E def fun(x=1,y=2):

```python
def fun(x=1,y=2)
```

F if m>3:

print("m大于3")

```python
if m > 3:
  print("m大于3")

```
