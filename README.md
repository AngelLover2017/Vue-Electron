# Vue-Elctron
如何将Electron与Vue结合起来使用，用Vue构建界面，用Electron做桌面程序适配？这里给出一个可行的方案。通过把[electron-quick-start](https://www.electronjs.org/docs/tutorial/first-app#%E5%B0%9D%E8%AF%95%E6%AD%A4%E4%BE%8B) 这个demo结合到Vue-CLI创建的脚手架里去，然后对 package.json里做一些脚本控制，形成一套完整的Vue+Electron开发流程。

# 整体的工作流

# 需要注意的点

这里有个奇怪的地方就是，我们无法在Vue中直接使用CommonJS规范的require函数去加载Electron模块，并用Webpack打包。如果你试图在Vue里这样去写：
```

```
