# Maplet
+ Maplet语法还是很有难度的，我们正在认真学习(作业暂时还无法完成)，以下:
1. Maplet Builder的确有很多奇怪的bug比如下拉框似乎会莫名其妙地消失，然后就全白做了
2. Maplet对应的.maplet似乎无法双击直接运行（不过官方文献似乎说可以？），所以要想使用maplet还是得用工作表打开，不过，就我认为，工作表是必须的，因为maplet里面有函数需要和工作表互动，比如下面图片中的这句：Button("OK", Shutdown("TF1"))。这句话的意思是在点击OK按钮后，关闭maplet，并且向工作表返回字符串"TF1"。因此，工作表示Maplet不可或缺的一部分。
3. 我们现在正在尝试使用maplet package编程maplet（就是用代码的形式），不过这似乎有点难度，官方也有教程，只要在maple帮助文献里面搜索Maplet就可以找到基础教程，这就是我现在正在做的。
![example](https://github.com/Hobo12/Maplet/blob/master/example.jpg)
