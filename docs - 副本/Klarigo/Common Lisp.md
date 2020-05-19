# Common Lisp

---

**Common Lisp**，缩写为**CL**（不是组合逻辑的缩写）是Lisp编程语言的一种方言，由ANSI INCITS  226-1994(R2004)（前身为ANSI X3.226-1994(R1999)），所定义的语言规范标准。Common Lisp  HyperSpec是源自于ANSI Common Lisp标准的网页超链接版本。 

CL语言是为标准化和改良Maclisp而开发的后继者。到20世纪80年代初，几个工作群组已经在设计MacLisp各种后继者，例如：Lisp  Machine Lisp（又名 ZetaLisp），Spice Lisp，NIL和S-1  Lisp。CL是为了标准化和扩展此前众多的MacLisp分支而开发，它本身并非具体的实作，而是对语言设立标准的规范。有数个实作符合Common  Lisp规范，其中包括自由和开源软件，以及商业化产品。CL支援了[结构化](https://zh.wikipedia.org/wiki/%E7%BB%93%E6%9E%84%E5%8C%96%E7%BC%96%E7%A8%8B)、[函数式](https://zh.wikipedia.org/wiki/%E5%87%BD%E6%95%B8%E7%A8%8B%E5%BC%8F%E8%AA%9E%E8%A8%80)和[面向对象编程](https://zh.wikipedia.org/wiki/%E9%9D%A2%E5%90%91%E5%AF%B9%E8%B1%A1%E7%A8%8B%E5%BA%8F%E8%AE%BE%E8%AE%A1)等范式。相对于各种嵌入在特定产品中的语言，如[Emacs Lisp](https://zh.wikipedia.org/wiki/Emacs_Lisp)和[AutoLISP](https://zh.wikipedia.org/wiki/AutoLISP)，Common Lisp是一种用途广泛的编程语言。不同于很多早期Lisp，Common Lisp如同Scheme，其中的变量是预设为词法[作用域](https://zh.wikipedia.org/wiki/%E4%BD%9C%E7%94%A8%E5%9F%9F)的。 

身为一种[动态编程语言](https://zh.wikipedia.org/wiki/%E5%8A%A8%E6%80%81%E8%AF%AD%E8%A8%80)，它有助于进化和[增量](https://zh.wikipedia.org/wiki/%E8%BF%AD%E4%BB%A3%E5%BC%8F%E5%BC%80%E5%8F%91)的软件开发，并将其迭代[编译](https://zh.wikipedia.org/wiki/%E7%B7%A8%E8%AD%AF%E5%99%A8)成高效的执行程序。这种增量开发通常是互动持续地改善，而不需中断执行中的应用程序。它还支援在后期的分析和优化阶段添加可选的型别注记与转型，使编译器产生更有效率的代码。例如在硬件和实作的支援范围内，`fixnum`能保存一个未封装整数，允许比[大整数](https://zh.wikipedia.org/wiki/%E5%A4%A7%E6%95%B0_(%E6%95%B0%E5%AD%A6))或[任意精度类型](https://zh.wikipedia.org/wiki/%E9%AB%98%E7%B2%BE%E5%BA%A6%E8%AE%A1%E7%AE%97)更高效率的运算。同样地，在每个模组或函数的基础上可声明优化，指示编译器要编译成哪一类型的安全级别。 

CL包含了支援[多分派](https://zh.wikipedia.org/wiki/%E5%A4%9A%E5%88%86%E6%B4%BE)和方法组合的物件系统，缩写为CLOS，它通常以元物件（Metaobject）协定来实现。 

CL借由标准功能进行扩展，例如Lisp宏（编译时期程序自身完成的代码重排（compile-time code  rearrangement accomplished by the program  itself））和阅读器宏（赋予用户自定义的语法以扩展具特殊意义的符号（extension of syntax to give special  meaning to characters reserved for users for this purpose））。 

CL为Maclisp和[约翰·麦卡锡](https://zh.wikipedia.org/wiki/%E7%BA%A6%E7%BF%B0%C2%B7%E9%BA%A6%E5%8D%A1%E9%94%A1)的原创Lisp提供了一些向后兼容性。这允许较旧的Lisp软件移植到Common Lisp之上。 