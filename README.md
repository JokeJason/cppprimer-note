# 目录（Table of Content）

<!-- TOC START -->

## [docs/CH00_Preface.md](docs/CH00_Preface.md)
- [开始](docs/CH00_Preface.md#开始)
- [前言](docs/CH00_Preface.md#前言)
- [为什么是这一本？](docs/CH00_Preface.md#为什么是这一本？)

## [docs/CH01_Getting_Started.md](docs/CH01_Getting_Started.md)
  - [最简单的 C++ 程序](docs/CH01_Getting_Started.md#最简单的-C-程序)
      - [关键概念：类型](docs/CH01_Getting_Started.md#关键概念类型)
      - [输入输出](docs/CH01_Getting_Started.md#输入输出)
  - [1.3 注释](docs/CH01_Getting_Started.md#13-注释)
  - [1.4 控制流](docs/CH01_Getting_Started.md#14-控制流)
    - [编译器的工作](docs/CH01_Getting_Started.md#编译器的工作)
    - [程序风格](docs/CH01_Getting_Started.md#程序风格)
  - [1.5 类的介绍](docs/CH01_Getting_Started.md#15-类的介绍)
    - [关键概念：类定义行为](docs/CH01_Getting_Started.md#关键概念类定义行为)
    - [关键术语](docs/CH01_Getting_Started.md#关键术语)

## [docs/CH02_Variables_and_Basic_Types.md](docs/CH02_Variables_and_Basic_Types.md)
  - [C++ 最基本特性](docs/CH02_Variables_and_Basic_Types.md#C-最基本特性)
  - [内置类型](docs/CH02_Variables_and_Basic_Types.md#内置类型)
  - [2.1 内置类型](docs/CH02_Variables_and_Basic_Types.md#21-内置类型)
    - [2.1.1 算术类型](docs/CH02_Variables_and_Basic_Types.md#211-算术类型)
      - [内置类型的机器级表示](docs/CH02_Variables_and_Basic_Types.md#内置类型的机器级表示)
      - [有符号和无符号类型](docs/CH02_Variables_and_Basic_Types.md#有符号和无符号类型)
      - [决定使用何种内置类型的建议](docs/CH02_Variables_and_Basic_Types.md#决定使用何种内置类型的建议)
    - [2.1.2 类型转换](docs/CH02_Variables_and_Basic_Types.md#212-类型转换)
    - [A6.1 类型提升](docs/CH02_Variables_and_Basic_Types.md#A61-类型提升)
    - [A6.2 整型转换](docs/CH02_Variables_and_Basic_Types.md#A62-整型转换)
    - [A6.3 整数和浮点数](docs/CH02_Variables_and_Basic_Types.md#A63-整数和浮点数)
    - [A6.4 浮点类型](docs/CH02_Variables_and_Basic_Types.md#A64-浮点类型)
    - [A6.5 算术转换](docs/CH02_Variables_and_Basic_Types.md#A65-算术转换)
    - [建议：避免未定义或者实现定义（implementation-defined）的行为](docs/CH02_Variables_and_Basic_Types.md#建议避免未定义或者实现定义implementation-defined的行为)
      - [算术表达式中有无符号类型](docs/CH02_Variables_and_Basic_Types.md#算术表达式中有无符号类型)
      - [注意：不要混用有符号和无符号类型](docs/CH02_Variables_and_Basic_Types.md#注意不要混用有符号和无符号类型)
    - [2.1.3 字面量](docs/CH02_Variables_and_Basic_Types.md#213-字面量)
      - [枚举](docs/CH02_Variables_and_Basic_Types.md#枚举)
  - [2.2 变量](docs/CH02_Variables_and_Basic_Types.md#22-变量)
    - [2.2.1 变量定义](docs/CH02_Variables_and_Basic_Types.md#221-变量定义)
      - [列初始化](docs/CH02_Variables_and_Basic_Types.md#列初始化)
      - [术语：什么是对象？](docs/CH02_Variables_and_Basic_Types.md#术语什么是对象？)
      - [默认初始化](docs/CH02_Variables_and_Basic_Types.md#默认初始化)
      - [注意：未初始化是一个很严重的 bug](docs/CH02_Variables_and_Basic_Types.md#注意未初始化是一个很严重的-bug)
    - [2.2.2 变量声明和定义](docs/CH02_Variables_and_Basic_Types.md#222-变量声明和定义)
      - [概念：静态类型](docs/CH02_Variables_and_Basic_Types.md#概念静态类型)
    - [2.2.3 标识符](docs/CH02_Variables_and_Basic_Types.md#223-标识符)
    - [2.2.4 名字的域](docs/CH02_Variables_and_Basic_Types.md#224-名字的域)
  - [2.3 复合类型](docs/CH02_Variables_and_Basic_Types.md#23-复合类型)
    - [2.3.1 引用](docs/CH02_Variables_and_Basic_Types.md#231-引用)
    - [2.3.2 指针](docs/CH02_Variables_and_Basic_Types.md#232-指针)
      - [指针的值](docs/CH02_Variables_and_Basic_Types.md#指针的值)
      - [建议：初始化所有指针](docs/CH02_Variables_and_Basic_Types.md#建议初始化所有指针)
      - [赋值和指针](docs/CH02_Variables_and_Basic_Types.md#赋值和指针)
      - [其它的指针操作](docs/CH02_Variables_and_Basic_Types.md#其它的指针操作)
      - [void* 指针](docs/CH02_Variables_and_Basic_Types.md#void-指针)
    - [2.3.3 理解复合类型声明](docs/CH02_Variables_and_Basic_Types.md#233-理解复合类型声明)
      - [指针的引用](docs/CH02_Variables_and_Basic_Types.md#指针的引用)
  - [2.4 const 限定符](docs/CH02_Variables_and_Basic_Types.md#24-const-限定符)
      - [默认情况下，const 变量不是全局变量](docs/CH02_Variables_and_Basic_Types.md#默认情况下，const-变量不是全局变量)
    - [2.4.1 const 的引用](docs/CH02_Variables_and_Basic_Types.md#241-const-的引用)
    - [2.4.2 指针和 const](docs/CH02_Variables_and_Basic_Types.md#242-指针和-const)
      - [const 指针](docs/CH02_Variables_and_Basic_Types.md#const-指针)
    - [2.4.3 顶层 const（Top-Level const）](docs/CH02_Variables_and_Basic_Types.md#243-顶层-constTop-Level-const)
    - [2.4.4 constexpr 和常量表达式](docs/CH02_Variables_and_Basic_Types.md#244-constexpr-和常量表达式)
      - [constexpr 变量](docs/CH02_Variables_and_Basic_Types.md#constexpr-变量)
      - [字面类型（Literal Types）](docs/CH02_Variables_and_Basic_Types.md#字面类型Literal-Types)
  - [2.5 类型处理](docs/CH02_Variables_and_Basic_Types.md#25-类型处理)
    - [2.5.1 类型别名](docs/CH02_Variables_and_Basic_Types.md#251-类型别名)
    - [2.5.2 auto 类型限定符](docs/CH02_Variables_and_Basic_Types.md#252-auto-类型限定符)
    - [2.5.3 decltype 类型说明符](docs/CH02_Variables_and_Basic_Types.md#253-decltype-类型说明符)
  - [2.6 自定义数据结构](docs/CH02_Variables_and_Basic_Types.md#26-自定义数据结构)
  - [术语](docs/CH02_Variables_and_Basic_Types.md#术语)

## [docs/CH03_Strings_Vectors_and_Arrays.md](docs/CH03_Strings_Vectors_and_Arrays.md)
  - [3.1 名称空间的 using 声明](docs/CH03_Strings_Vectors_and_Arrays.md#31-名称空间的-using-声明)
  - [3.2 string 类型](docs/CH03_Strings_Vectors_and_Arrays.md#32-string-类型)
    - [3.2.2 string 可执行的操作](docs/CH03_Strings_Vectors_and_Arrays.md#322-string-可执行的操作)
      - [将字面量与 string 字符串相加](docs/CH03_Strings_Vectors_and_Arrays.md#将字面量与-string-字符串相加)
    - [3.2.3 处理 string 中的字符](docs/CH03_Strings_Vectors_and_Arrays.md#323-处理-string-中的字符)
  - [3.3 vector 类型](docs/CH03_Strings_Vectors_and_Arrays.md#33-vector-类型)
    - [3.3.1 定义和初始化 vector](docs/CH03_Strings_Vectors_and_Arrays.md#331-定义和初始化-vector)
    - [3.3.2 添加元素到 vector 中](docs/CH03_Strings_Vectors_and_Arrays.md#332-添加元素到-vector-中)
    - [3.3.3 vector 的其它操作](docs/CH03_Strings_Vectors_and_Arrays.md#333-vector-的其它操作)
  - [3.4 介绍迭代器](docs/CH03_Strings_Vectors_and_Arrays.md#34-介绍迭代器)
    - [3.4.1 使用迭代器](docs/CH03_Strings_Vectors_and_Arrays.md#341-使用迭代器)
      - [迭代器类型](docs/CH03_Strings_Vectors_and_Arrays.md#迭代器类型)
      - [迭代器算术运算](docs/CH03_Strings_Vectors_and_Arrays.md#迭代器算术运算)
  - [3.5 数组](docs/CH03_Strings_Vectors_and_Arrays.md#35-数组)
      - [显式初始化数组元素](docs/CH03_Strings_Vectors_and_Arrays.md#显式初始化数组元素)
      - [理解复杂数组声明](docs/CH03_Strings_Vectors_and_Arrays.md#理解复杂数组声明)
    - [3.5.2 访问数组元素](docs/CH03_Strings_Vectors_and_Arrays.md#352-访问数组元素)
    - [3.5.3 指针和数组](docs/CH03_Strings_Vectors_and_Arrays.md#353-指针和数组)
      - [指针是语言定义的迭代器](docs/CH03_Strings_Vectors_and_Arrays.md#指针是语言定义的迭代器)
      - [标准库 begin 和 end 函数](docs/CH03_Strings_Vectors_and_Arrays.md#标准库-begin-和-end-函数)
      - [指针算术运算](docs/CH03_Strings_Vectors_and_Arrays.md#指针算术运算)
      - [指针和下标操作](docs/CH03_Strings_Vectors_and_Arrays.md#指针和下标操作)
    - [3.5.4 C 风格字符串](docs/CH03_Strings_Vectors_and_Arrays.md#354-C-风格字符串)
- [3.5.5 提供给旧代码的接口](docs/CH03_Strings_Vectors_and_Arrays.md#355-提供给旧代码的接口)
  - [3.6 多维数组](docs/CH03_Strings_Vectors_and_Arrays.md#36-多维数组)
    - [多维数组的下标引用](docs/CH03_Strings_Vectors_and_Arrays.md#多维数组的下标引用)
  - [关键术语](docs/CH03_Strings_Vectors_and_Arrays.md#关键术语)

## [docs/CH04_Expressions.md](docs/CH04_Expressions.md)
  - [4.1 fundamentals](docs/CH04_Expressions.md#41-fundamentals)
    - [4.1.1 基础概念](docs/CH04_Expressions.md#411-基础概念)
    - [4.1.2 优先级和结合性](docs/CH04_Expressions.md#412-优先级和结合性)
    - [4.1.3 求值顺序](docs/CH04_Expressions.md#413-求值顺序)
  - [4.2 算数运算符](docs/CH04_Expressions.md#42-算数运算符)
  - [4.3 逻辑和关系操作符](docs/CH04_Expressions.md#43-逻辑和关系操作符)
      - [相等测试与 bool 字面量](docs/CH04_Expressions.md#相等测试与-bool-字面量)
  - [4.4 赋值操作符](docs/CH04_Expressions.md#44-赋值操作符)
      - [复合赋值运算符](docs/CH04_Expressions.md#复合赋值运算符)
  - [4.5 自增和自减操作符](docs/CH04_Expressions.md#45-自增和自减操作符)
  - [4.6 成员运算符](docs/CH04_Expressions.md#46-成员运算符)
  - [4.7 条件操作符](docs/CH04_Expressions.md#47-条件操作符)
  - [4.8 位（bitwise）操作符](docs/CH04_Expressions.md#48-位bitwise操作符)
      - [位移（bitwise shift）操作符](docs/CH04_Expressions.md#位移bitwise-shift操作符)
      - [位与、或、异或操作符](docs/CH04_Expressions.md#位与、或、异或操作符)
      - [sizeof 操作符](docs/CH04_Expressions.md#sizeof-操作符)
  - [4.10 逗号操作符](docs/CH04_Expressions.md#410-逗号操作符)
  - [4.11 类型转换](docs/CH04_Expressions.md#411-类型转换)
    - [4.11.2 其它隐式转换](docs/CH04_Expressions.md#4112-其它隐式转换)
    - [4.11.3 显式转换](docs/CH04_Expressions.md#4113-显式转换)
      - [static_cast](docs/CH04_Expressions.md#static_cast)
      - [const_cast](docs/CH04_Expressions.md#const_cast)
      - [reinterpret_cast](docs/CH04_Expressions.md#reinterpret_cast)
      - [C 风格强转](docs/CH04_Expressions.md#C-风格强转)
  - [4.12 操作符优先级](docs/CH04_Expressions.md#412-操作符优先级)

## [docs/CH05_Statements.md](docs/CH05_Statements.md)
- [if 语句](docs/CH05_Statements.md#if-语句)
- [switch 语句](docs/CH05_Statements.md#switch-语句)
- [while 语句](docs/CH05_Statements.md#while-语句)
- [do-while 语句](docs/CH05_Statements.md#do-while-语句)
- [for 语句](docs/CH05_Statements.md#for-语句)
- [goto 语句](docs/CH05_Statements.md#goto-语句)
- [异常处理](docs/CH05_Statements.md#异常处理)
  - [警告：C++ 中很难达到异常安全](docs/CH05_Statements.md#警告C-中很难达到异常安全)
  - [标准异常](docs/CH05_Statements.md#标准异常)

## [docs/CH06_Functions.md](docs/CH06_Functions.md)
  - [6.1 函数基础](docs/CH06_Functions.md#61-函数基础)
    - [6.1.1 形参和实参](docs/CH06_Functions.md#611-形参和实参)
    - [6.1.2 返回类型](docs/CH06_Functions.md#612-返回类型)
    - [6.1.3 本地变量](docs/CH06_Functions.md#613-本地变量)
    - [6.1.4 函数声明](docs/CH06_Functions.md#614-函数声明)
    - [6.1.5 分离编译（Separate Compilation）](docs/CH06_Functions.md#615-分离编译Separate-Compilation)
  - [6.2 参数传递](docs/CH06_Functions.md#62-参数传递)
    - [6.2.1 按值传递](docs/CH06_Functions.md#621-按值传递)
    - [6.2.2 按引用传递](docs/CH06_Functions.md#622-按引用传递)
    - [6.2.3 const 形参和实参](docs/CH06_Functions.md#623-const-形参和实参)
    - [6.2.4 数组形参](docs/CH06_Functions.md#624-数组形参)
    - [6.2.5 main：处理命令行参数](docs/CH06_Functions.md#625-main处理命令行参数)
    - [6.2.6 不定形参](docs/CH06_Functions.md#626-不定形参)
  - [6.3 返回类型和 return 语句](docs/CH06_Functions.md#63-返回类型和-return-语句)
    - [6.3.1 函数没有返回值](docs/CH06_Functions.md#631-函数没有返回值)
    - [6.3.2 函数有返回值](docs/CH06_Functions.md#632-函数有返回值)
    - [6.3.3 函数返回指向数组的指针](docs/CH06_Functions.md#633-函数返回指向数组的指针)
  - [6.4 函数重载（Overloaded Functions）](docs/CH06_Functions.md#64-函数重载Overloaded-Functions)
    - [6.4.1 重载和作用域](docs/CH06_Functions.md#641-重载和作用域)
  - [6.5 C++ 函数特殊特性](docs/CH06_Functions.md#65-C-函数特殊特性)
    - [6.5.1 默认实参（Default Arguments）](docs/CH06_Functions.md#651-默认实参Default-Arguments)
    - [6.5.2 内联函数和 constexpr 函数](docs/CH06_Functions.md#652-内联函数和-constexpr-函数)
    - [6.5.3 辅助 Debugging 的特性](docs/CH06_Functions.md#653-辅助-Debugging-的特性)
  - [6.6 函数调用匹配](docs/CH06_Functions.md#66-函数调用匹配)
    - [6.6.1 实参类型转换](docs/CH06_Functions.md#661-实参类型转换)
  - [6.7 函数指针](docs/CH06_Functions.md#67-函数指针)
  - [关键术语](docs/CH06_Functions.md#关键术语)

## [docs/CH07_Classes.md](docs/CH07_Classes.md)
  - [7.1 定义抽象数据类型](docs/CH07_Classes.md#71-定义抽象数据类型)
    - [7.1.1 设计类](docs/CH07_Classes.md#711-设计类)
    - [7.1.2 定义类](docs/CH07_Classes.md#712-定义类)
    - [7.1.3 定义类相关的非成员函数](docs/CH07_Classes.md#713-定义类相关的非成员函数)
    - [7.1.4 构造函数](docs/CH07_Classes.md#714-构造函数)
    - [7.1.5 拷贝、赋值和析构](docs/CH07_Classes.md#715-拷贝、赋值和析构)
  - [7.2 访问控制和封装](docs/CH07_Classes.md#72-访问控制和封装)
    - [7.2.1 友元](docs/CH07_Classes.md#721-友元)
  - [7.3 其它类特性](docs/CH07_Classes.md#73-其它类特性)
    - [7.3.1 类成员](docs/CH07_Classes.md#731-类成员)
    - [7.3.2 返回 `*this` 的函数](docs/CH07_Classes.md#732-返回-this-的函数)
    - [7.3.3 类类型](docs/CH07_Classes.md#733-类类型)
    - [7.3.4 友元再探](docs/CH07_Classes.md#734-友元再探)
  - [7.4 类作用域](docs/CH07_Classes.md#74-类作用域)
    - [7.4.1 名称查找和类作用域](docs/CH07_Classes.md#741-名称查找和类作用域)
  - [7.5 构造函数再探](docs/CH07_Classes.md#75-构造函数再探)
    - [7.5.1 构造初始值列表](docs/CH07_Classes.md#751-构造初始值列表)
    - [7.5.2 委托构造函数](docs/CH07_Classes.md#752-委托构造函数)
    - [7.5.3 默认构造函数的角色](docs/CH07_Classes.md#753-默认构造函数的角色)
    - [7.5.4 隐式类类型转换](docs/CH07_Classes.md#754-隐式类类型转换)
    - [7.5.5 聚合类](docs/CH07_Classes.md#755-聚合类)
    - [7.5.6 字面类](docs/CH07_Classes.md#756-字面类)
  - [7.6 static 成员](docs/CH07_Classes.md#76-static-成员)
  - [关键概念](docs/CH07_Classes.md#关键概念)

## [docs/CH08_The_IO_Library.md](docs/CH08_The_IO_Library.md)
  - [8.1 IO 类](docs/CH08_The_IO_Library.md#81-IO-类)
    - [8.1.1 不能拷贝或赋值 IO 对象](docs/CH08_The_IO_Library.md#811-不能拷贝或赋值-IO-对象)
    - [8.1.2 条件状态](docs/CH08_The_IO_Library.md#812-条件状态)
    - [8.1.3 管理输出缓冲](docs/CH08_The_IO_Library.md#813-管理输出缓冲)
  - [8.2 文件输入输出](docs/CH08_The_IO_Library.md#82-文件输入输出)
    - [8.2.1 使用文件流对象](docs/CH08_The_IO_Library.md#821-使用文件流对象)
    - [8.2.2 文件模式](docs/CH08_The_IO_Library.md#822-文件模式)
  - [8.3 string 流](docs/CH08_The_IO_Library.md#83-string-流)
    - [8.3.1 使用 istringstream 对象](docs/CH08_The_IO_Library.md#831-使用-istringstream-对象)
    - [8.3.2 使用 ostringstream 对象](docs/CH08_The_IO_Library.md#832-使用-ostringstream-对象)
  - [关键概念](docs/CH08_The_IO_Library.md#关键概念)

## [docs/CH09_Sequential_Containers.md](docs/CH09_Sequential_Containers.md)
  - [9.1 顺序容器概述](docs/CH09_Sequential_Containers.md#91-顺序容器概述)
  - [9.2 容器库概述](docs/CH09_Sequential_Containers.md#92-容器库概述)
    - [9.2.1 迭代器](docs/CH09_Sequential_Containers.md#921-迭代器)
    - [9.2.2 容器类型的成员](docs/CH09_Sequential_Containers.md#922-容器类型的成员)
    - [9.2.3 begin 和 end 成员](docs/CH09_Sequential_Containers.md#923-begin-和-end-成员)
    - [9.2.4 定义和初始化容器](docs/CH09_Sequential_Containers.md#924-定义和初始化容器)
    - [9.2.5 赋值和 swap](docs/CH09_Sequential_Containers.md#925-赋值和-swap)
    - [9.2.6 容器 size 操作](docs/CH09_Sequential_Containers.md#926-容器-size-操作)
    - [9.2.7 关系操作符](docs/CH09_Sequential_Containers.md#927-关系操作符)
  - [9.3 顺序容器操作](docs/CH09_Sequential_Containers.md#93-顺序容器操作)
    - [9.3.1 给顺序容器添加元素](docs/CH09_Sequential_Containers.md#931-给顺序容器添加元素)
    - [9.3.2 访问元素](docs/CH09_Sequential_Containers.md#932-访问元素)
    - [9.3.3 移除元素](docs/CH09_Sequential_Containers.md#933-移除元素)
    - [9.3.4 特定于 `forward_list` 的操作](docs/CH09_Sequential_Containers.md#934-特定于-forward_list-的操作)
    - [9.3.5 resize 容器大小](docs/CH09_Sequential_Containers.md#935-resize-容器大小)
    - [9.3.6 容器操作会使得迭代器失效](docs/CH09_Sequential_Containers.md#936-容器操作会使得迭代器失效)
  - [9.4 vector 如何增长](docs/CH09_Sequential_Containers.md#94-vector-如何增长)
  - [9.5 额外的 string 操作](docs/CH09_Sequential_Containers.md#95-额外的-string-操作)
    - [9.5.1 构建 string 的其它方式](docs/CH09_Sequential_Containers.md#951-构建-string-的其它方式)
    - [9.5.2 改变 string 的其它方式](docs/CH09_Sequential_Containers.md#952-改变-string-的其它方式)
    - [9.5.3 string 搜索操作](docs/CH09_Sequential_Containers.md#953-string-搜索操作)
    - [9.5.4 compare 函数](docs/CH09_Sequential_Containers.md#954-compare-函数)
    - [9.5.5 数字转换](docs/CH09_Sequential_Containers.md#955-数字转换)
  - [9.6 容器适配器](docs/CH09_Sequential_Containers.md#96-容器适配器)
  - [关键术语](docs/CH09_Sequential_Containers.md#关键术语)

## [docs/CH10_Generic_Algorithms.md](docs/CH10_Generic_Algorithms.md)
  - [10.1 概述](docs/CH10_Generic_Algorithms.md#101-概述)
  - [10.2 算法入门](docs/CH10_Generic_Algorithms.md#102-算法入门)
    - [10.2.1 只读算法](docs/CH10_Generic_Algorithms.md#1021-只读算法)
    - [10.2.2 写容器元素的算法](docs/CH10_Generic_Algorithms.md#1022-写容器元素的算法)
    - [10.2.3 对容器元素进行重排序的算法](docs/CH10_Generic_Algorithms.md#1023-对容器元素进行重排序的算法)
  - [10.3 定制操作](docs/CH10_Generic_Algorithms.md#103-定制操作)
    - [10.3.1 传递函数给算法](docs/CH10_Generic_Algorithms.md#1031-传递函数给算法)
    - [10.3.2 lambda 表达式](docs/CH10_Generic_Algorithms.md#1032-lambda-表达式)
    - [10.3.3 lambda 捕获和返回](docs/CH10_Generic_Algorithms.md#1033-lambda-捕获和返回)
    - [10.3.4 绑定实参](docs/CH10_Generic_Algorithms.md#1034-绑定实参)
  - [10.4 再谈迭代器](docs/CH10_Generic_Algorithms.md#104-再谈迭代器)
    - [10.4.1 插入迭代器](docs/CH10_Generic_Algorithms.md#1041-插入迭代器)
    - [10.4.2 iostream 迭代器](docs/CH10_Generic_Algorithms.md#1042-iostream-迭代器)
    - [10.4.3 反向迭代器](docs/CH10_Generic_Algorithms.md#1043-反向迭代器)
  - [10.5 通用算法的分类](docs/CH10_Generic_Algorithms.md#105-通用算法的分类)
    - [10.5.1 按照5种迭代器分类](docs/CH10_Generic_Algorithms.md#1051-按照5种迭代器分类)
    - [10.5.2 按照算法的参数模式分配](docs/CH10_Generic_Algorithms.md#1052-按照算法的参数模式分配)
    - [10.5.3 算法名字的约定](docs/CH10_Generic_Algorithms.md#1053-算法名字的约定)
  - [10.6 特定于容器的算法](docs/CH10_Generic_Algorithms.md#106-特定于容器的算法)

## [docs/CH11_Associative_Containers.md](docs/CH11_Associative_Containers.md)
  - [11.1 使用关联容器](docs/CH11_Associative_Containers.md#111-使用关联容器)
  - [11.2 关联容器简介](docs/CH11_Associative_Containers.md#112-关联容器简介)
    - [11.2.1 定义关联容器](docs/CH11_Associative_Containers.md#1121-定义关联容器)
    - [11.2.2 对于 key 类型的要求](docs/CH11_Associative_Containers.md#1122-对于-key-类型的要求)
    - [11.2.3 pair 类型](docs/CH11_Associative_Containers.md#1123-pair-类型)
  - [11.3 关联容器的操作](docs/CH11_Associative_Containers.md#113-关联容器的操作)
    - [11.3.1 关联容器迭代器](docs/CH11_Associative_Containers.md#1131-关联容器迭代器)
    - [11.3.2 添加元素](docs/CH11_Associative_Containers.md#1132-添加元素)
    - [11.3.3 移除元素](docs/CH11_Associative_Containers.md#1133-移除元素)
    - [11.3.4 map 的下标操作](docs/CH11_Associative_Containers.md#1134-map-的下标操作)
    - [11.3.5 访问元素](docs/CH11_Associative_Containers.md#1135-访问元素)
  - [11.4 无序容器](docs/CH11_Associative_Containers.md#114-无序容器)

## [docs/CH12_Dynamic_Memory.md](docs/CH12_Dynamic_Memory.md)
  - [12.1 动态内存和智能指针](docs/CH12_Dynamic_Memory.md#121-动态内存和智能指针)
    - [12.1.1 `shared_ptr` 类](docs/CH12_Dynamic_Memory.md#1211-shared_ptr-类)
    - [12.1.2 直接管理内存](docs/CH12_Dynamic_Memory.md#1212-直接管理内存)
    - [12.1.3 将 `shared_ptr` 运用于 new](docs/CH12_Dynamic_Memory.md#1213-将-shared_ptr-运用于-new)
    - [12.1.4 智能指针和异常](docs/CH12_Dynamic_Memory.md#1214-智能指针和异常)
    - [12.1.5 `unique_ptr`](docs/CH12_Dynamic_Memory.md#1215-unique_ptr)
    - [12.1.6 `weak_ptr`](docs/CH12_Dynamic_Memory.md#1216-weak_ptr)
  - [12.2 动态数组](docs/CH12_Dynamic_Memory.md#122-动态数组)
    - [12.2.1 new 和数组](docs/CH12_Dynamic_Memory.md#1221-new-和数组)
    - [12.2.2 allocator 类](docs/CH12_Dynamic_Memory.md#1222-allocator-类)
  - [关键术语](docs/CH12_Dynamic_Memory.md#关键术语)

## [docs/CH13_Copy_Control.md](docs/CH13_Copy_Control.md)
  - [13.1 拷贝、赋值和销毁](docs/CH13_Copy_Control.md#131-拷贝、赋值和销毁)
    - [13.1.1 拷贝构造函数](docs/CH13_Copy_Control.md#1311-拷贝构造函数)
    - [13.1.2 拷贝-赋值操作符](docs/CH13_Copy_Control.md#1312-拷贝-赋值操作符)
    - [13.1.3 析构函数](docs/CH13_Copy_Control.md#1313-析构函数)
    - [13.1.4 三/五法则](docs/CH13_Copy_Control.md#1314-三五法则)
    - [13.1.5 使用 `=default`](docs/CH13_Copy_Control.md#1315-使用-default)
    - [13.1.6 禁用拷贝](docs/CH13_Copy_Control.md#1316-禁用拷贝)
  - [13.2 拷贝控制和资源管理](docs/CH13_Copy_Control.md#132-拷贝控制和资源管理)
    - [13.2.1 类像值一样](docs/CH13_Copy_Control.md#1321-类像值一样)
    - [13.2.2 定义类像指针一样](docs/CH13_Copy_Control.md#1322-定义类像指针一样)
  - [13.3 交换](docs/CH13_Copy_Control.md#133-交换)
  - [13.4 拷贝控制实例](docs/CH13_Copy_Control.md#134-拷贝控制实例)
  - [13.5 管理动态内存的类](docs/CH13_Copy_Control.md#135-管理动态内存的类)
  - [13.6 移动对象](docs/CH13_Copy_Control.md#136-移动对象)
    - [13.6.1 右值引用](docs/CH13_Copy_Control.md#1361-右值引用)
    - [13.6.2 移动构造函数和移动赋值](docs/CH13_Copy_Control.md#1362-移动构造函数和移动赋值)
    - [13.6.3 右值引用和成员函数](docs/CH13_Copy_Control.md#1363-右值引用和成员函数)
  - [关键术语](docs/CH13_Copy_Control.md#关键术语)

## [docs/CH14_Overloaded_Operations_and_Conversions.md](docs/CH14_Overloaded_Operations_and_Conversions.md)
  - [14.1 基本概念](docs/CH14_Overloaded_Operations_and_Conversions.md#141-基本概念)
  - [14.2 输入输出操作符](docs/CH14_Overloaded_Operations_and_Conversions.md#142-输入输出操作符)
    - [14.2.1 重载输出操作符 `<<`](docs/CH14_Overloaded_Operations_and_Conversions.md#1421-重载输出操作符-)
    - [14.2.2 重载输入操作符 `>>`](docs/CH14_Overloaded_Operations_and_Conversions.md#1422-重载输入操作符-)
  - [14.3 算术和关系操作符](docs/CH14_Overloaded_Operations_and_Conversions.md#143-算术和关系操作符)
    - [14.3.1 相等操作符](docs/CH14_Overloaded_Operations_and_Conversions.md#1431-相等操作符)
    - [14.3.2 关系操作符](docs/CH14_Overloaded_Operations_and_Conversions.md#1432-关系操作符)
  - [14.4 赋值操作符](docs/CH14_Overloaded_Operations_and_Conversions.md#144-赋值操作符)
  - [14.5 下标操作符](docs/CH14_Overloaded_Operations_and_Conversions.md#145-下标操作符)
  - [14.6 自增和自减操作符](docs/CH14_Overloaded_Operations_and_Conversions.md#146-自增和自减操作符)
  - [14.7 成员访问操作符](docs/CH14_Overloaded_Operations_and_Conversions.md#147-成员访问操作符)
  - [14.8 函数调用操作符](docs/CH14_Overloaded_Operations_and_Conversions.md#148-函数调用操作符)
    - [14.8.1 Lambdas 是函数对象](docs/CH14_Overloaded_Operations_and_Conversions.md#1481-Lambdas-是函数对象)
    - [14.8.2 标准库中的函数对象](docs/CH14_Overloaded_Operations_and_Conversions.md#1482-标准库中的函数对象)
    - [14.8.3 可调用对象和 std::function](docs/CH14_Overloaded_Operations_and_Conversions.md#1483-可调用对象和-stdfunction)
  - [14.9 重载、转换和操作符](docs/CH14_Overloaded_Operations_and_Conversions.md#149-重载、转换和操作符)
    - [14.9.1 转换操作符](docs/CH14_Overloaded_Operations_and_Conversions.md#1491-转换操作符)
    - [14.9.2 避免转换二义性](docs/CH14_Overloaded_Operations_and_Conversions.md#1492-避免转换二义性)
    - [14.9.3 函数匹配和重载操作符](docs/CH14_Overloaded_Operations_and_Conversions.md#1493-函数匹配和重载操作符)

## [docs/CH15_Object-Oriented_Programming.md](docs/CH15_Object-Oriented_Programming.md)
  - [15.1 面向对象：介绍](docs/CH15_Object-Oriented_Programming.md#151-面向对象介绍)
  - [15.2 定义基类和子类](docs/CH15_Object-Oriented_Programming.md#152-定义基类和子类)
    - [15.2.1 定义基类](docs/CH15_Object-Oriented_Programming.md#1521-定义基类)
    - [15.2.2 定义子类](docs/CH15_Object-Oriented_Programming.md#1522-定义子类)
    - [15.2.3 转换和继承](docs/CH15_Object-Oriented_Programming.md#1523-转换和继承)
  - [15.3 虚函数](docs/CH15_Object-Oriented_Programming.md#153-虚函数)
  - [15.4 抽象基类](docs/CH15_Object-Oriented_Programming.md#154-抽象基类)
  - [15.5 访问控制与继承](docs/CH15_Object-Oriented_Programming.md#155-访问控制与继承)
  - [15.6 继承下的类作用域](docs/CH15_Object-Oriented_Programming.md#156-继承下的类作用域)
  - [15.7 构造函数与拷贝控制](docs/CH15_Object-Oriented_Programming.md#157-构造函数与拷贝控制)
    - [15.7.1 虚析构函数](docs/CH15_Object-Oriented_Programming.md#1571-虚析构函数)
    - [15.7.2 合成拷贝控制和继承](docs/CH15_Object-Oriented_Programming.md#1572-合成拷贝控制和继承)
    - [15.7.3 子类拷贝控制成员](docs/CH15_Object-Oriented_Programming.md#1573-子类拷贝控制成员)
    - [15.7.4 继承的构造函数](docs/CH15_Object-Oriented_Programming.md#1574-继承的构造函数)
  - [15.8 容器和继承](docs/CH15_Object-Oriented_Programming.md#158-容器和继承)
  - [关键术语](docs/CH15_Object-Oriented_Programming.md#关键术语)

## [docs/CH16_Templates_and_Generic_Programming.md](docs/CH16_Templates_and_Generic_Programming.md)
  - [16.1 定义模板](docs/CH16_Templates_and_Generic_Programming.md#161-定义模板)
    - [16.1.1 函数模板](docs/CH16_Templates_and_Generic_Programming.md#1611-函数模板)
    - [16.1.2 类模板](docs/CH16_Templates_and_Generic_Programming.md#1612-类模板)
    - [16.1.3 模板参数](docs/CH16_Templates_and_Generic_Programming.md#1613-模板参数)
    - [16.1.4 成员模板](docs/CH16_Templates_and_Generic_Programming.md#1614-成员模板)
    - [16.1.5 控制实例化](docs/CH16_Templates_and_Generic_Programming.md#1615-控制实例化)
    - [16.1.6 效率和灵活性](docs/CH16_Templates_and_Generic_Programming.md#1616-效率和灵活性)
  - [16.2 模板实参推断](docs/CH16_Templates_and_Generic_Programming.md#162-模板实参推断)
    - [16.2.1 转换和模板类型参数](docs/CH16_Templates_and_Generic_Programming.md#1621-转换和模板类型参数)
    - [16.2.2 函数模板显式实参](docs/CH16_Templates_and_Generic_Programming.md#1622-函数模板显式实参)
    - [16.2.3 Trailing Return Types and Type Transformation](docs/CH16_Templates_and_Generic_Programming.md#1623-Trailing-Return-Types-and-Type-Transformation)
    - [16.2.4 函数指针和实参推断](docs/CH16_Templates_and_Generic_Programming.md#1624-函数指针和实参推断)
    - [16.2.5 模板实参推断和引用](docs/CH16_Templates_and_Generic_Programming.md#1625-模板实参推断和引用)
    - [16.2.6 理解 `std::move`](docs/CH16_Templates_and_Generic_Programming.md#1626-理解-stdmove)
    - [16.2.7 Forwarding](docs/CH16_Templates_and_Generic_Programming.md#1627-Forwarding)
  - [16.3 重载和模板](docs/CH16_Templates_and_Generic_Programming.md#163-重载和模板)
  - [16.4 可变参数模板](docs/CH16_Templates_and_Generic_Programming.md#164-可变参数模板)
    - [16.4.1 书写可变参数函数模板](docs/CH16_Templates_and_Generic_Programming.md#1641-书写可变参数函数模板)
    - [16.4.2 包扩展（Pack Expansion）](docs/CH16_Templates_and_Generic_Programming.md#1642-包扩展Pack-Expansion)
    - [16.4.3 转发参数包（Forwarding Parameter Packs）](docs/CH16_Templates_and_Generic_Programming.md#1643-转发参数包Forwarding-Parameter-Packs)
  - [16.5 模板特例（Template Sepcializations）](docs/CH16_Templates_and_Generic_Programming.md#165-模板特例Template-Sepcializations)
  - [关键术语](docs/CH16_Templates_and_Generic_Programming.md#关键术语)

## [docs/CH17_Specialized_Library_Facilities.md](docs/CH17_Specialized_Library_Facilities.md)
  - [17.1 tuple 类型](docs/CH17_Specialized_Library_Facilities.md#171-tuple-类型)
    - [17.1.1 定义和初始化 tuple](docs/CH17_Specialized_Library_Facilities.md#1711-定义和初始化-tuple)
    - [17.1.2 使用 tuple 以返回多个值](docs/CH17_Specialized_Library_Facilities.md#1712-使用-tuple-以返回多个值)
    - [17.2 bitset 类型](docs/CH17_Specialized_Library_Facilities.md#172-bitset-类型)
    - [17.2.1 定义和初始化 bitset](docs/CH17_Specialized_Library_Facilities.md#1721-定义和初始化-bitset)
    - [17.2.2 bitset 上的操作](docs/CH17_Specialized_Library_Facilities.md#1722-bitset-上的操作)
  - [17.3 正则表达式](docs/CH17_Specialized_Library_Facilities.md#173-正则表达式)
    - [17.3.1 使用正则表达式库](docs/CH17_Specialized_Library_Facilities.md#1731-使用正则表达式库)
    - [17.3.2 匹配和正则迭代器类型](docs/CH17_Specialized_Library_Facilities.md#1732-匹配和正则迭代器类型)
    - [17.3.3 使用子表达式](docs/CH17_Specialized_Library_Facilities.md#1733-使用子表达式)
    - [17.3.4 使用 `regex_replace`](docs/CH17_Specialized_Library_Facilities.md#1734-使用-regex_replace)
  - [随机数](docs/CH17_Specialized_Library_Facilities.md#随机数)
    - [17.4.1 随机数引擎和分布](docs/CH17_Specialized_Library_Facilities.md#1741-随机数引擎和分布)
    - [17.4.2 其它类型的分布](docs/CH17_Specialized_Library_Facilities.md#1742-其它类型的分布)
  - [17.5 再谈 IO 库](docs/CH17_Specialized_Library_Facilities.md#175-再谈-IO-库)
    - [17.5.1 格式化输入和输出](docs/CH17_Specialized_Library_Facilities.md#1751-格式化输入和输出)
    - [17.5.2 未格式化的输入、输出操作](docs/CH17_Specialized_Library_Facilities.md#1752-未格式化的输入、输出操作)
    - [17.5.3 随机访问流](docs/CH17_Specialized_Library_Facilities.md#1753-随机访问流)

## [docs/CH18_Tools_for_Large_Programs.md](docs/CH18_Tools_for_Large_Programs.md)
  - [18.1 异常处理](docs/CH18_Tools_for_Large_Programs.md#181-异常处理)
    - [18.1.1 抛出异常](docs/CH18_Tools_for_Large_Programs.md#1811-抛出异常)
    - [18.1.2 捕捉异常](docs/CH18_Tools_for_Large_Programs.md#1812-捕捉异常)
    - [18.1.3 函数级 try 语句块和构造函数](docs/CH18_Tools_for_Large_Programs.md#1813-函数级-try-语句块和构造函数)
    - [18.1.4 noexcept 异常说明符](docs/CH18_Tools_for_Large_Programs.md#1814-noexcept-异常说明符)
    - [18.1.5 异常类层级](docs/CH18_Tools_for_Large_Programs.md#1815-异常类层级)
  - [18.2 名称空间](docs/CH18_Tools_for_Large_Programs.md#182-名称空间)
    - [18.2.1 名称空间定义](docs/CH18_Tools_for_Large_Programs.md#1821-名称空间定义)
    - [18.2.2 使用名称空间的成员](docs/CH18_Tools_for_Large_Programs.md#1822-使用名称空间的成员)
    - [18.2.3 类、名称空间和作用域](docs/CH18_Tools_for_Large_Programs.md#1823-类、名称空间和作用域)
    - [18.2.4 重载和名称空间](docs/CH18_Tools_for_Large_Programs.md#1824-重载和名称空间)
  - [18.3 多重继承和虚继承](docs/CH18_Tools_for_Large_Programs.md#183-多重继承和虚继承)
    - [18.3.1 多重继承](docs/CH18_Tools_for_Large_Programs.md#1831-多重继承)
    - [18.3.2 转换和多基类](docs/CH18_Tools_for_Large_Programs.md#1832-转换和多基类)
    - [18.3.3 多重继承下的类作用域](docs/CH18_Tools_for_Large_Programs.md#1833-多重继承下的类作用域)
    - [18.3.4 虚继承](docs/CH18_Tools_for_Large_Programs.md#1834-虚继承)
    - [18.3.5 构造函数和虚继承](docs/CH18_Tools_for_Large_Programs.md#1835-构造函数和虚继承)
  - [关键术语](docs/CH18_Tools_for_Large_Programs.md#关键术语)

## [docs/CH19_Specialized_Tools_and_Techniques.md](docs/CH19_Specialized_Tools_and_Techniques.md)
  - [19.1 控制内存分配](docs/CH19_Specialized_Tools_and_Techniques.md#191-控制内存分配)
    - [19.1.1 重载 new 和 delete](docs/CH19_Specialized_Tools_and_Techniques.md#1911-重载-new-和-delete)
    - [19.1.2 定位（placement）new 表达式](docs/CH19_Specialized_Tools_and_Techniques.md#1912-定位placementnew-表达式)
  - [19.2 运行时类型识别](docs/CH19_Specialized_Tools_and_Techniques.md#192-运行时类型识别)
    - [19.2.1 `dynamic_cast` 操作符](docs/CH19_Specialized_Tools_and_Techniques.md#1921-dynamic_cast-操作符)
    - [19.2.2 typeid 操作符](docs/CH19_Specialized_Tools_and_Techniques.md#1922-typeid-操作符)
    - [19.2.3 使用 RTTI](docs/CH19_Specialized_Tools_and_Techniques.md#1923-使用-RTTI)
    - [19.2.4 `type_info` 类](docs/CH19_Specialized_Tools_and_Techniques.md#1924-type_info-类)
  - [19.3 枚举](docs/CH19_Specialized_Tools_and_Techniques.md#193-枚举)
  - [19.4 类成员指针（Pointer to Class Member）](docs/CH19_Specialized_Tools_and_Techniques.md#194-类成员指针Pointer-to-Class-Member)
    - [19.4.1 指向数据成员的指针](docs/CH19_Specialized_Tools_and_Techniques.md#1941-指向数据成员的指针)
    - [19.4.2 指向成员函数的指针](docs/CH19_Specialized_Tools_and_Techniques.md#1942-指向成员函数的指针)
    - [19.4.3 将成员函数用作可调用对象](docs/CH19_Specialized_Tools_and_Techniques.md#1943-将成员函数用作可调用对象)
  - [19.5 嵌套类](docs/CH19_Specialized_Tools_and_Techniques.md#195-嵌套类)
  - [19.6 union : 空间节约型的类](docs/CH19_Specialized_Tools_and_Techniques.md#196-union--空间节约型的类)
  - [19.7 本地类](docs/CH19_Specialized_Tools_and_Techniques.md#197-本地类)
  - [19.8 固有的不可移植特性](docs/CH19_Specialized_Tools_and_Techniques.md#198-固有的不可移植特性)
    - [19.8.1 位域（bit-fields）](docs/CH19_Specialized_Tools_and_Techniques.md#1981-位域bit-fields)
    - [19.8.2 volatile 限定符](docs/CH19_Specialized_Tools_and_Techniques.md#1982-volatile-限定符)
    - [19.8.3 链接指令：`extern "C"`](docs/CH19_Specialized_Tools_and_Techniques.md#1983-链接指令extern-C)

<!-- TOC END -->