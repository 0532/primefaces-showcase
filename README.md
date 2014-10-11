###primefaces-showcase
===================
**primefaces-demo的源码，可运行版**

一个创建分支（branch）的流程 

参考流程

1. 首先fork项目
2. 把fork过去的项目也就是你的项目clone到你的本地
3. 在命令行运行 `git branch develop` 来创建一个新分支
4. 运行 `git checkout develop` 来切换到新分支
5. 运行 `git remote add upstream https://github.com/numbbbbb/the-swift-programming-language-in-chinese.git` 把我的库添加为远端库
6. 运行 `git remote update`更新
7. 运行 `git fetch upstream gh-pages` 拉取我的库的更新到本地
8. 运行 `git rebase upstream/gh-pages` 将我的更新合并到你的分支

这是一个初始化流程，只需要做一遍就行，之后请一直在develop分支进行翻译。

如果翻译过程中我的库有了更新，请重复6、7、8步。

翻译完成之后，首先push到你的库，然后登录GitHub，在你的库的首页可以看到一个 `pull request` 按钮，点击它，填写一些说明信息，然后提交即可。

或者先在 网页上设置好分支，然后，使用github for windows 在提交代码的时候选择要提交的分支即可
