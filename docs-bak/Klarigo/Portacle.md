# Portacle

---

##  *感谢日本的大神 Shirakumo，打造了这个 Common Lisp 的 IDE！*



## portacle, 一种可移植的通用lisp开发环境

​	Portacle是Common Lisp的完整IDE，可以通过USB随身携带。它是多平台的，可以在Windows，OS X和Linux上运行。由于不需要任何复杂的安装过程，因此可以立即进行**设置**和**运行**

​           它非常适合只需要一个良好起点的Lisp的绝对初学者，也适合希望尽量减少准备一切的时间的高级用户。         







---

## 如何使用

**需要注意的是，Portacle是个IDE集成工具，需要在桌面环境下使用，而不是命令行**

安装并启动后，它可能会等待几秒钟，然后展示一个类似于一下内容的窗口：

![portacle1](img/portacle1.png)

### 区域划分

窗口分为两个区域，每个区域个各显示一个缓冲区，目前位于上方的是Scratch缓冲区，而下方的是Lisp缓冲区。

### 快速测试

作为测试，请在Lisp提示缓冲区内单机，并输入以下代码：

```lisp
(progn (format T "Hey, what's your name?~%")
       (format T "Hello, ~a!" (read-line)))
```

**不难发现，Portacle会自动匹配括号和引号**

如果想运行这段代码，只需要通过单机或使用方向键将光标移到末尾，按下Enter（回车）键即可。

![portacle2](img\portacle2.png)

**恭喜！目前为止，在Portacle上的第一个程序就已经完成了！开始你的Lisp之旅吧！**

更多详细内容，请访问Portacle官方网站：https://portacle.github.io/