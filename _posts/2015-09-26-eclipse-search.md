# 如何改变Eclipse默认Search Tab

不能理解为何eclipse默认的Open Search Dialog (^H)是打开Java Search，实际上90%以上的情况我都要开File Search.

很遗憾暂时没有找到可以修改这个设置的方法，但是有一个变通方案如下：
- 打开Preferences > General > Keys
- 找到Open Search Dialog （可以通过filter），可以看到他bind在^H。Unbind Command。
- 找到 File Search，在Binding输入框内按Ctrl+H
- Apply

这样子Ctrl+H就绑定到File Search，相当于我要的效果。

其他Search tab请递推。

## 另
Search Dialog里的tabs可以去除，点击Search Dialog左下角的Customize，去掉不要的即可。
