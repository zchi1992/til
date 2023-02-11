# Today I learned 
Programming, computing techniques, Algorithm trading notes, etc. I learned day to day. Inspired by [simonw/til](https://github.com/simonw/til) and [jbranchaud/til](https://github.com/jbranchaud/til).

## TODO:
- [ ]  list timestamp at the beginning
- [ ]  make a local repository

## VSCode
2023-02-07 Working with container in VSCode [Dev Container](https://code.visualstudio.com/docs/devcontainers/containers)

## Docker
2023-01-21 Went through docker start guide

## C++
2023-01-30 短时间内学习了C++基本语法，编译流程和LLVM framework  
2023-02-08 Difference between `std::vector` and `std::array`.  
2023-02-09 Access Modifier: public, private, protected, friends.  
2023-02-09 keywords: virtue, using, static, namespace


## CMake
Went through [CMake tutorial](https://cmake.org/cmake/help/latest/guide/tutorial/index.html#introduction) - 2023-01-24

## LLVM
2023-01-24 LLVM framework    
2023-02-09 LLVM BasicBlocks, FunctionPass, Iterator.  
2023-02-09 
`align <n> or align(<n>)`  
> This indicates that the pointer value or vector of pointers has the specified alignment. If applied to a vector of pointers, all pointers (elements) have the specified alignment. If the pointer value does not have the specified alignment, poison value is returned or passed instead. The align attribute should be combined with the noundef attribute to ensure a pointer is aligned, or otherwise the behavior is undefined. Note that align 1 has no effect on non-byval, non-preallocated arguments.  

Note that this attribute has additional semantics when combined with the byval or preallocated attribute, which are documented there.  

## Clang
Went through [Make/Makefile intro](https://www.gnu.org/software/make/manual/html_node/Introduction.html) - 2023-01-24

## Python
Pandas library以及数据存储和读取方式 - 2023-01-15

## Linux/Unix
### 2023-02-06 Linux file descriptor/redirection
[What is Redirection?](https://www.guru99.com/linux-redirection.html)
`>`: STDOUT redirection
`>>`: STDOUT redirection but only append rather than overwritting
`2>`: STDERR redirection
`<`: STDIN redirection
`ls Documents ABC> dirlist 2>&1` STDERR redirects to target of STDOUT, which is dirlist file


## Algorithms
Array and LinkedList - 2022-12-28

## Software Testing
Fuzzing - 2023-01-20
Korat - test generation tools - 2023-01-30
Randoop - test generation tools - 2023-01-31
2023-02-04 Dataflow analysis: Reaching Definition Analysis, Available Expression Analysis, Live Variable Analysis, Very Busy Expression Analysis

## Algorithm Trading and HFT
上周完成了Order Imbalance分析 - 2023-01-16

Trading Costs and Electronic Markets - 2022-12-25

IPO tickers are collected using PAD API which uses Bloomberg APIs. The IPO information is not used by ATP placement. Checked ICO information on CoinGecKo but it only shows new coins on CoinGecKo. We can monitor ICO tickers for any trading opportunities. - 2023-01-31
