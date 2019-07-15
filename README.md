# go-mud —— Go 语言写的 MUD 客户端

本项目实现目标是一个 MUD 客户端，主要采用 Go 语言实现。

本项目基于中国知名 MUD 游戏《[北大侠客行](http://www.pkuxkx.com)》开发，但也应该可以适用于其它 MUD 服务。

## 如何使用本程序

### 运行环境

+ 本程序可在 Linux 及 macOS 上运行。运行时不依赖其它软件。
+ 建议golang版本 >= 1.11

### 启动并进入北侠
+ Linux
```
  > echo 'export GO111MODULE=on'>>/etc/profile
  > echo 'export GOPROXY=https://goproxy.io'>>/etc/profile
  > source /etc/profile
  > cd $GOPATH/src
  > git clone https://github.com/dzpao/go-mud.git
  > cd go-mud
  > git submodule update --init
  > go run main.go
```

+ Windows
```
待完善
```

### 通过 Docker 来启动

本项目支持通过 Docker 来运行，推荐使用 Docker 来挂机。

```
待完善
```

## 本程序有什么用

**本程序目前仍在开发当中，并不完善。** 但已经能够提供必要的功能来登录 MUD 服务器。且有许多亮点：

* [X] 原生支持 UTF-8
* [X] 纯文本界面，通过命令行和快捷键来操作
* [X] 支持 macOS、Linux、Windows、安卓四大平台
* [X] 支持 32 位和 64 位操作系统
* [X] 支持 [Lua 机器人](https://github.com/dzpao/lua-mud-robots)

## 本程序不能做什么

* 不支持图形界面，没有丰富的代码编辑框或诸如此类的其它 UI 元素来帮助你写触发和机器人
* 没有庞大的用户群，没有大量开箱即用的机器人，对伸手党不友好

## 如何贡献

* 体验
* 通过[提交 issue](https://github.com/dzpao/go-mud/issues/new) 来反馈意见
* 通过 PR 来贡献代码
