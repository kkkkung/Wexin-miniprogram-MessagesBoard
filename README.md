# MessageBoard
# Wexin-miniprogram-MessagesBoard

PHP后端代码是直接原生写的，很乱。而且对于一个前端开发者来说搭建PHP运行环境是个不友好的事情，所以写了一个 Node 后端，PHP 里的代码有很多PHP的开发基础点，也很适合拿来学习。

如果想用该项目来要了解微信小程序开发，建议用项目中Node文件夹的搭建后端，把项目跑起来。

怎么运行，在 Node文件夹中的 README.MD中有

Node 文件夹也有很值得模仿的地方，用Express写MVC架构

`pages/index/index.js` 是小程序与后端交互的重点，可以试一试自己把数据 console.log 出来观察一下。

小程序布局很简单，就一个页面。采用了的是[WeUi](https://github.com/Tencent/weui-wxss/)

想开发一个东西，就去做，卡壳了上[官网看文档](https://developers.weixin.qq.com/miniprogram/dev/) 。