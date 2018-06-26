# Why Rust

From [rust home page](https://www.rust-lang.org/en-US/):

**Rust** is a systems programming language that runs blazingly fast, prevents segfaults, and guarantees thread safety.


---

## Background

- 效率，效率，效率
- 硬件的多核
- 软件的并发
- 软件的安全

![history](https://www.ibm.com/developerworks/library/os-developers-know-rust/Figure01.png)

---

## Programming Language Comparison 1

|         |学习成本  | 执行效率| 高并发 | 运行依赖 | 包管理  |
|---------|---------|---------|-------|---------|---------|
| c++     |    10   |    10   |  8    |   no    |    3    |
| go      |    6    |    7    |  10   |   no    |    7    |
| java    |    9    |    9    |  8    |   jvm   |    7    |
| python  |    6    |    7    |  6    | python  |    7    |
| js      |    7    |    7    |  6    | node    |    10   |
| rust    |    8    |    10   |  9    |   no    |    10   |


---

## Programming Language Comparison 2

|         |安全性   |内存管理  |类型系统| 表达能力 | 跨平台  |
|---------|---------|---------|-------|---------|---------|
| c++     |    8    | by hand |  10   | 复杂    |  一般    |
| go      |    8    |    gc   |  10   | 一般    |  好     |
| java    |    9    |    gc   |  8    | 复杂    |  好     |
| python  |    7    |    gc   |  6    | 强      |  好     |
| js      |    7    |    gc   |  6    | 强      |  好     |
| rust    |    10   |  auto   |  9    | 强      |  好     |


## Programming Language Comparison

- 面向对象
- 函数式编程 （stream，iterator）
- 元编译（generic，宏， 反射）

---

## Features

* zero-cost abstractions
* move semantics
* guaranteed memory safety
* threads without data races
* trait-based generics
* pattern matching
* type inference
* minimal runtime
* efficient C bindings

---

## Effective

- 新手的代码可以放心提交
- 更少的bug
- 更快的开发效率
- 长期整体成本的降价

---

## rust的项目

- 操作系统: Redox
- 数据库: TiKV
- 浏览器内核：Servo
- 区块链: parity
- 搜索引擎: tanvity
- 服务器: Aticx, Hyper,
- 游戏引擎: Piston
- 嵌入式: 
- Web Assembly

---

## rust大神的rust视频介绍
- [vedio1](https://www.youtube.com/watch?v=agzf6ftEsLU)
- [vedio2](https://www.youtube.com/watch?v=lO1z-7cuRYI)

---

### learn by example
- [通过例子学-rust(中文版)](https://rustwiki.org/zh-CN//rust-by-example/index.html)

### 中文版rust Primer
- [rust Primer](https://rustcc.gitbooks.io/rustprimer/content/)
- Programming Rust

### 24 days of rust
- [24 days of rust](http://zsiciarz.github.io/24daysofrust/)

---
 
### rust社区大本营
- [reddit](https://www.reddit.com/r/rust/)

### rust学习qq群
- QQ: 303838735

---

## 你的手边Rust文档：
```sh
$ rustup doc
```

---

## Levelup

1. 熟悉rust的语义语法，可以看懂代码
2. 熟悉rust的标准库，可以写出简单代码
3. 逐渐积累沉淀，开始总结各种常见的最佳实践（惯用法和模式）
4. 和rust编译器成为亲密伙伴
5. 广泛了解各个领域的有代表性第三方库（社区）
6. 能够完成rust的各种规模的项目
7. 贡献社区

