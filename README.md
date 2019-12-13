# The-Road-of-Devepment-Operations
让我们开始开发吧！马上拿出一个可以Run的App，你需要它 -> DevOps


## 你需要做的

### 拿到了一台 Mac
#### 安装 brew
#### 安装IDE
以 VsCode 为例
安装同步工具，同步。用 settings-sync 来同步你的个人插件集 （需要登录 Github）。

#### 优化 Terminal

没什么好说的，我们就用这个非常棒的教程：
https://www.robertcooper.me/elegant-development-experience-with-zsh-and-hyper-terminal
(除此之外你应该还会想到加一个https://github.com/zsh-users/zsh-autosuggestions/blob/master/INSTALL.md)

两个配置文件，请到这个项目的根目录找
.zshrc
.hyper.js

#### 安装JS开发环境
我用NVM

#### 配置SSH
很多时候，你会用到 SSH 来访问一些 远程 被加密 的资源，这时候你需要用 SSH 密钥 生成器 生成的私钥和公钥，公钥 用来 与 远程通讯。你在访问远程资源时， 如果需要 SSH 协议， mac 电脑会自动带上 匹配你的私钥，这时候如果你的私钥存放位置不是 mac 默认的位置，就麻烦了。那如何 在指定位置生成密钥对呢？
这篇文章可以告诉你：
https://superuser.com/questions/1004254/how-can-i-change-the-directory-that-ssh-keygen-outputs-to

