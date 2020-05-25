# Common Lisp

---

## 维基百科

**Common Lisp**，缩写为**CL**（不是组合逻辑的缩写）是Lisp编程语言的一种方言，由ANSI INCITS  226-1994(R2004)（前身为ANSI X3.226-1994(R1999)），所定义的语言规范标准。Common Lisp  HyperSpec是源自于ANSI Common Lisp标准的网页超链接版本。 

CL语言是为标准化和改良Maclisp而开发的后继者。到20世纪80年代初，几个工作群组已经在设计MacLisp各种后继者，例如：Lisp  Machine Lisp（又名 ZetaLisp），Spice Lisp，NIL和S-1  Lisp。CL是为了标准化和扩展此前众多的MacLisp分支而开发，它本身并非具体的实作，而是对语言设立标准的规范。有数个实作符合Common  Lisp规范，其中包括自由和开源软件，以及商业化产品。CL支援了**结构化**、**函数式**和**面向对象编程**等范式。相对于各种嵌入在特定产品中的语言，如[Emacs Lisp](https://zh.wikipedia.org/wiki/Emacs_Lisp)和[AutoLISP](https://zh.wikipedia.org/wiki/AutoLISP)，Common Lisp是一种用途广泛的编程语言。不同于很多早期Lisp，Common Lisp如同Scheme，其中的变量是预设为词法作用域的。 

身为一种[动态编程语言](https://zh.wikipedia.org/wiki/%E5%8A%A8%E6%80%81%E8%AF%AD%E8%A8%80)，它有助于进化和**增量**的软件开发，并将其**迭代编译**成高效的执行程序。这种增量开发通常是互动持续地改善，而不需中断执行中的应用程序。它还支援在后期的分析和优化阶段添加可选的型别注记与转型，使编译器产生更有效率的代码。例如在硬件和实作的支援范围内，`fixnum`能保存一个未封装整数，允许比**大整数**或**任意精度类型**更高效率的运算。同样地，在每个模组或函数的基础上可声明优化，指示编译器要编译成哪一类型的安全级别。 

CL包含了支援[多分派](https://zh.wikipedia.org/wiki/%E5%A4%9A%E5%88%86%E6%B4%BE)和方法组合的物件系统，缩写为CLOS，它通常以元物件（Metaobject）协定来实现。 

CL借由标准功能进行扩展，例如Lisp宏（编译时期程序自身完成的代码重排（compile-time code  rearrangement accomplished by the program  itself））和阅读器宏（赋予用户自定义的语法以扩展具特殊意义的符号（extension of syntax to give special  meaning to characters reserved for users for this purpose））。 

CL为Maclisp和[约翰·麦卡锡](https://zh.wikipedia.org/wiki/%E7%BA%A6%E7%BF%B0%C2%B7%E9%BA%A6%E5%8D%A1%E9%94%A1)的原创Lisp提供了一些向后兼容性。这允许较旧的Lisp软件移植到Common Lisp之上。 



## Lisp语言的历史

​	在20世纪50年代末，MIT在研究人工智能（**AI**）和符号计算的时候开发了Lisp程序设计语言，Lisp是**List Processor**的缩写，列表是Lisp的主要数据结构。
 	Lisp的优点在于它的**简单性**和**灵活性**。他被广泛用于探索式编程，这是一种软件开发风格，系统的开发是**增量式**的，根据实验评价的结果可能会对系统做出根本性的改变。探索式编程也用于AI程序的开发，由于程序员无法预知程序会怎样去完成一项工作，只有通过多次测试才能知道，著名的文本编辑器**Emacs**就是用Lisp编写而成的，还有Linux的图形工具箱GTK以及目前在各种计算机环境下使用的很多程序都是用Lisp编写的。

​	在过去的多年中，已经开发出了多种Lisp工具，形成了各种不同的语言版本。期中一个很具影响力的版本是**Maclisp**，他是20世纪60年代在MIT的MAC项目中开发出来的。另外一个是**Scheme**，是由MIT的 Guy Steele 和 Gerald Sussman 在70年代开发出来的。现代的Lisp是Common Lisp，它引入了面向对象原语的复杂形式，与Scheme合称现代两大Lisp方言，标准由**ANSI X3.226-1994**定义。