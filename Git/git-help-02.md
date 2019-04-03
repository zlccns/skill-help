## Git 安装

由于 Git 的出现就是为了更好的管理 Linux 内核，所以最早是运行在 `Linux` 和 `Unix` 上的，*_( `MAC`是基于 Unix，所以对 Git 有着天然的支持 )_*，而随着 Git 的迅速普及，慢慢也支持了 `Windows`，时至今日， Git 已经可以在各大主流系统上正常运行了

这里**假设你正在使用 MAC 做开发，且未安装Git**，想要安装有两种方法：

* 通过 homebrew 安装
* 通过 Xcode 安装

#### 通过 homebrew 安装

[homebrew](https://brew.sh/index_zh-cn) 是 `MAC` 的软件包的管理器，算是 MAC 开发的必备工具之一，话不多说，我们进入正题；

首先打开 `MAC` 的命令行工具：

```
启动台 > 其他 > 终端
```
然后，输入如下命令，并等待安装完成：

```bash
# 2019.04.x
# 如果当前时间非常落后，请参考homebrew的文档进行安装: https://brew.sh/index_zh-cn
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```

安装完成之后，执行如下命令，即可安装 Git：

```bash
brew install git
```

#### 通过 Xcode 安装

[Xcode](https://developer.apple.com/xcode/) 是苹果官方的免费IDE，是开发 Mac/ios 的必备工具，而 Xcode 集成了 Git ，你只需要登录 `App Store` 下载 Xcode ，在其中 `Install` 即可：

```
Xcode > Preferences > Downloads > Command Line Tools
```
