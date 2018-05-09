> This is the Simplified Chinese translation of *[mostly-adequate-guide](https://github.com/MostlyAdequate/mostly-adequate-guide)*, thank Professor Franklin Frisby for his great work!

## 关于翻译

之前已有[llh911001](https://github.com/llh911001/mostly-adequate-guide-chinese)的中文翻译。但不知道翻译基于原文哪个版本。原文内容和章节有一些更新，也加入了在线练习。基于以上原因我使用fork创建了一个版本。这样原文更新了能merge回来再翻译，有利于保持更新。翻译过程中会参考 llh911001 的版本，也欢迎有人和我一起来翻译。

[![cover](/images/cover.png)](SUMMARY.md)

## 关于本书

这本书的主题是函数范式（Functional Paradigm 简称 FP）。我们将使用世界上最流行的函数式编程语言：JavaScript。一些人可能会觉得这个选择并不明智，因为现在的主流观点认为它是一门命令式（imperative）的语言，并不适合用来讲函数式。但我认为这是学习函数式编程的最好方式，因为：


 * **你很可能每天在工作中使用它。**

    这让你有机会付诸实践，每天在实际编程中学以致用比在空余时间用一门深奥的函数式语言做玩具项目更好。


 * **我们不必在开始写程序之前学会所有（函数式知识）。**

    在纯函数式语言中，你必须使用 monad 才能输出变量或者读取 DOM 节点。这里我们可以走捷径——学习把代码转变成函数式。这门语言页更容易入门因为它是多范式语言，你可以在有知识空缺时使用你现在的方式实践。


 * **这门语言完全能写高级的函数式代码。**


    只需一两个微型的库就能帮助我们模拟 Scala 或 Haskell 中想要的所有特性。虽然面向对象程序设计（Object-oriented programing）正主导业界，但在 JavaScript 中用起来显然不方便。用起来就像在高速公路上露营或者穿着橡胶套鞋跳踢踏舞一样。我们不得不到处使用 `bind` 以免 `this` 改变。没有类可以用（目前还没有），为了应对忘记使用 `new` 关键字后的怪异行为我们有各种变通方法，私有成员只能通过闭包（closure）才能实现。对我们许多人来说，无论如何函数式编程看起来都更加自然。

以上说明，强类型的函数式编程语言无疑将成为本书呈现编码风格的最佳场所。JavaScript 将是我们学习函数式的手段，应用到什么地方取决于你。幸运的是，接口都是数学的，因此也是普适的。最终你会发现你习惯了 Swiftz, Scalaz, Haskell, PureScript 以及其他的数学向的语言环境。


## 在线阅读

最好的阅读体验, [使用Gitbook在线阅读](https://mostly-adequate.gitbooks.io/mostly-adequate-guide/).

- 快速响应的侧边栏
- 在浏览器中练习
- 深入的例子


## 下载

* [下载 PDF](https://www.gitbook.com/download/pdf/book/mostly-adequate/mostly-adequate-guide)
* [下载 EPUB](https://www.gitbook.com/download/epub/book/mostly-adequate/mostly-adequate-guide)
* [下载 Mobi (Kindle)](https://www.gitbook.com/download/mobi/book/mostly-adequate/mostly-adequate-guide)


## 自己尝试

```
git clone https://github.com/MostlyAdequate/mostly-adequate-guide.git
cd mostly-adequate-guide/
npm install
npm run setup
gitbook pdf
```


# 目录

见 [SUMMARY.md](SUMMARY.md)

### 参与贡献

见 [CONTRIBUTING.md](/CONTRIBUTING.md)

### 翻译

见 [TRANSLATIONS.md](TRANSLATIONS.md)

### FAQ

见 [FAQ.md](FAQ.md)



# 未来计划

* **第 1 部分** （第1-7章） 是基础知识指南。这是初版草稿，所以我会及时更正发现的的错误。欢迎提供帮助！
* **第 2 部分** （第8-10章） 讲述类型类（type class），比如函子（functor） 和 单子（monad），最后会讲到到 traversable。我希望能塞进来一些 monad transformer 相关的知识，再写一个纯函数的应用。
* **第 3 部分** （第11+章）将开始游走于编程实践与学术之间。我们将看到 comonad、f-algebra、free monad、yoneda 以及其他一些范畴学概念。


---


<p align="center">
  <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">
    <img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" />
  </a>
  <br />
  This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.
</p>
