# Readmify

## 什么是"Readmify"

Readmify是一种代码风格标准,可以适用于包括但不限于C,C++,JavaScript,PHP,GoLang等等编程语言.Readmify本质上是markdown与各种编程语言的代码杂交.

## 目标

使代码与文档完美结合在一起,用编译器编译时能输出可执行文件,用markdown查看器查看时看到的是代码和文档.

## 示例详见test1.md

## 已知问题

图例:
  - [ ] 待解决的问题
  - [X] 已经解决的问题
  - 不会去解决的问题

问题列表:
  - 文件开头和代码框开头有猎奇的`/*`
  - [ ] 英文文档
  - 文言文文档
  - [ ] go在编译时拓展名如果是md就编译不了
  - [ ] 实现自动化,即`readmify.exe --code test1.cxx --doc test1.txt`然后就输出了结合后的test1.md
  - [ ] 实现"Readmify IDE"
