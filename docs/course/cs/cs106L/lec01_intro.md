---
comments: true
---

# 课程介绍

## 关于 CS106L

- **重点在于代码**: 怎样让代码变得更好，优雅的代码应该是怎么样的
- 理解 C++ 是怎么产生和发展的
- 深入了解 STL

## C++ 的历史
### 汇编语言

#### 优势

- **简单**的指令集
- 运行速度快(如果代码写得好)
- 可以**完全控制**你的程序

#### 不足

- 代码写的很冗长(即使是执行简单的任务)
- 代码很难理解
- 通用性很差(很难跨平台工作)

### C 语言的出现

#### 优势

- 更快
- 更简单
- 跨平台

#### 不足

- **没有对象和类型**
- 很难写出 "通用代码"
- 编写大型项目很吃力

### C++ 的设计理念

> [C++ 核心指南](https://isocpp.github.io/CppCoreGuidelines/CppCoreGuidelines)

- 只添加用于解决实际问题的特性
- 在代码中直接表达想法和意图
- **区块化(Compartmentalization)** 是关键
- 不要浪费时间或空间
- 尽可能在**编译时**保证安全

### 关于 STL

- 功能性齐全, 包括常用的函数和一些算法
- 内置多种类, 比如 maps, sets, vectors
- 通过 namespace `std::` 来使用 STL 中的内容
- 功能强大并且一直在更新维护
