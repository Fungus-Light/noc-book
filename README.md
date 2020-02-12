
# The Nature of Code 《代码本质》中文版

_**源仓库已经不再更新! 原作者开始在写新版，请看这里 [noc-book-2](https://github.com/nature-of-code/noc-book-2)!**_

_**（fungus-light）虽然这是一本已经不再更新的书籍，但是我还是准备尝试着去翻译一下，一方面磨练自己的技术，另一方面也是方便大家**_

你好啊。如果你找到这里，你就找到了我的书《代码本质》的原始材料. 这本书在[natureofcode.com](http://www.natureofcode.com)有纸质和PDF档出售. 那里你同样可以找到免费的网页版.  

你可能已经注意到了，这本书所有的原材料都在这里 —— 插图, 原始文本(html), 以及样式表(CSS).  这本书通过[Creative Commons Attribution-NonCommercial 3.0 Unported License](http://creativecommons.org/licenses/by-nc/3.0/)开源. 你可以免费的分享和改编这本书, 只要你标明出处并且不重新出售（非商业用途）。

所有书中代码遵循[MIT License](http://opensource.org/licenses/MIT)开源.

（fungus-light）由我改编后的JavaScript代码也同样遵循**MIT**协议开源。

通过再GitHub上托管这本书的原材料, 我希望能更方便修改和更正错误.  请使用GitHub issues来汇报bug, 打字错误, 建议, 不啦不啦.  你也可以fork一份，然后自己修订然后发起pull request.

（fungus-light）事实上这本书并不是第一版，之前还有更老的版本:-)。  

当前版本的原文仓库 [The Magic Book](https://github.com/magicbookproject/magicbook)。

最老的版本[Nature of Code archived repo](https://github.com/shiffman/The-Nature-of-Code-archive).

# 编译步骤
**注：为了和cnpm相适应，我稍微修改了里面的依赖。基本不影响。**

**magicbook依赖于princexml这个程序，国内下载很慢，所以一定要先下载安装princexml并配置完环境变量（windows）再安装magicbook**

* 安装 [node.js](https://nodejs.org/en/).
* 在终端中输入（中国国内用户推荐使用cnpm） ([more info here](https://github.com/magicbookproject/magicbook/)):
```
npm install magicbook -g
```
* 克隆或者(或者下载) 这个仓库.
* 在终端里, 进入仓库的目录.
* 输入指令:
```
npm install
magicbook build
```
* 在**build**文件夹里面可以看到编译完的内容.

###### Build Notes
在Mac OSX, 你需要同时安装princexml以及 node-prince `brew cask install prince` 或者在[这里](http://www.princexml.com/download/)下载。

更多关于Magic Book，查看[它的README](https://github.com/magicbookproject/magicbook/blob/master/README.md).
