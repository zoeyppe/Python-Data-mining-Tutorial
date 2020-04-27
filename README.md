# Python数据挖掘教程
> **作者**：长行\
> **说明**：本教程以周为阶段，每周包括5天的知识内容(Day)、1天的案例实现(Example)和1天的小测验(Test)；此外还可能包含选学部分(Extra)。
> 案例的难度比小测验的难度更高；每周可能有多个小测验，只要任选其一完成即可。

### Week1 - Python语言基础（一）
#### Day01 - Hello World
* Python简介
* 搭建Python开发环境
* Hello World
* 输入和输出
* IDE - Jupyter, PyCharm(Community)
> 练习题：运行py文件、IDE中的Hello World、用户输入名字
#### Day02 - 语言元素
* 变量和类型 -
 [常用变量类型与基础运算](https://github.com/Changxing97/Python-Data-mining-Tutorial/blob/master/Week-01/%E5%B8%B8%E7%94%A8%E5%8F%98%E9%87%8F%E7%B1%BB%E5%9E%8B%E4%B8%8E%E5%9F%BA%E7%A1%80%E8%BF%90%E7%AE%97.ipynb)
* 变量命名
* 数值变量基础操作
* 字符串基础操作
* 运算符
> 练习题：华氏温度转换为摄氏温度、计算圆的周长和面积、计算有效互动比
#### Day03 - 程序运行流程
* 分支结构
* if语句
* 循环结构
* for循环
* while循环
> 练习题：百分制成绩转换为等级制成绩、输入三条边长判断能否构成三角形
> 练习题：判断是否为质数、打印九九乘法表、判断是否未互质数
#### Day04 - 常用数据类型操作
* 字符串常用操作
> 练习题：双色球选号、逗号分隔
* 列表常用操作(选学)
* 字典常用操作(选学)
* 集合常用操作(选学)
* 元组常用操作(选学)
#### Day05 - 函数
* 函数的作用
* 函数的定义
* 函数的调用
* 函数的参数
* 函数的返回值
> 练习题：将计算有效互动比的方法写为函数并调用、迭代实现菲波那切数列
* 函数的作用域(选学)
#### Extra01 - 算法思维基础
#### Example-01 - 鸡兔同笼问题
#### Test-01 - [登录问题](https://github.com/Changxing97/Python-Data-mining-Tutorial/blob/master/Week-01/Test-01-%E7%99%BB%E5%BD%95%E9%97%AE%E9%A2%98.md)
#### Test-02 - [牛吃草问题](https://github.com/Changxing97/Python-Data-mining-Tutorial/blob/master/Week-01/Test-02-%E7%89%9B%E5%90%83%E8%8D%89%E9%97%AE%E9%A2%98.md)
### Week-02 - Python语言基础（二）
#### Day06 - 正则表达式
* 字符串的高级操作 
* 使用正则表达式
* 正则表达式基础
> 练习题：手机号提取、邮箱提取、提取网页源代码中的url、清理Twitter的Url
#### Day07 - 数据存储
* 文件读写
* csv格式
* json格式
> 练习题：转存Json格式数据
#### Day08 - Python常用内置函数和模块
* time
* datetime
> 练习题：程序暂停1秒、输出文本格式日期
#### Day09 - 线程和进程
* 线程和进程的概念
* 使用进程
* 使用线程
> 练习题：多线程报数实验
#### Day10 - Excel文档读写
* openpyxl
> 练习题：读取Json文件写入到Excel、读取Excel文件写入到Json
#### Extra02 - Python的高级特性
* 切片器
* 迭代器
* 列表生成式
* 生成器
* 迭代器
#### Example-02 - 全唐诗文本格式整理(无对象应用)
#### Test-03 - [直播间弹幕数据清洗](https://github.com/Changxing97/Python-Data-mining-Tutorial/blob/master/Week-02/Test-03-%E7%9B%B4%E6%92%AD%E9%97%B4%E5%BC%B9%E5%B9%95%E6%95%B0%E6%8D%AE%E6%B8%85%E6%B4%97.md)
### Week-03 : Python语言基础（三）
#### Day11 - 面对对象编程基础
* 类与对象
* 定义类
* 使用对象
* 抽象、峰状、继承、多态
> 练习题1：定义媒体类
> 练习题2：定义一个圆类Circle，要求根据半径实例化，并包含可以返回圆的圆积、周长的方法
#### Day12 - 面对对象编程进阶
* 属性
* 方法
* 运算符重载
* 关联、继承、依赖
> 练习题：编写一个媒体类Media，要求如下：
> * 包含一个计数器的属性，可以统计一共实例化了多少个媒体
> * 实例化时获取媒体名、媒体网址，并包含可以返回媒体名、媒体网址的方法
> * 重写媒体类的__str__方法，另其返回媒体名
#### Day13 - 访问网络资源
* 计算机网络基础
* HTTP协议
* 访问网络资源
* 异常处理
* API的调用
> 练习题：完成一次网络请求、某个API的调用
#### Day14 - SQL语言基础
* DDL - 数据定义语言
* DML - 数据操作语言
* DCL - 数据控制语言
* 数据库操作软件：Navicat Premium 12、DataGrip
> 练习题：创建自己数据库、创建查询
#### Day15 - MySQL应用
* Python操作数据库
> 练习题：读取数据库写入到Excel、读取数据库写入到Json
#### Extra03 - numpy
#### Extra04 - HanLP
> 练习题：中文分词
#### Extra05 - Pillow
#### Example-03 : 诗词格律分析工具
#### Test-04 - [地图查询工具](https://github.com/Changxing97/Python-Data-mining-Tutorial/blob/master/Week-03/Test-04-%E5%9C%B0%E5%90%8D%E6%9F%A5%E8%AF%A2%E5%99%A8.md)
#### Test-05 - [24点算法实现](https://github.com/Changxing97/Python-Data-mining-Tutorial/blob/master/Week-03/Test-05-24%E7%82%B9%E7%AE%97%E6%B3%95%E5%AE%9E%E7%8E%B0.md)
#### Test-06 - 电梯算法(仅算法部分)
