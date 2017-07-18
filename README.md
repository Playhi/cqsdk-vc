[中文](https://github.com/Playhi/cqsdk-vc#中文版本) - [English](https://github.com/Playhi/cqsdk-vc#english)
# 中文版本
## 简介
* 使用 Visual C++ 编写酷Q应用。

## 状态
* Appveyor：<a href="https://ci.appveyor.com/project/Playhi/cqsdk-vc" target="_blank"><img src="https://ci.appveyor.com/api/projects/status/github/playhi/cqsdk-vc?branch=playhi"></a>

## 开发指引
* 请访问 [https://d.cqp.me/Pro/开发](https://d.cqp.me/Pro/%E5%BC%80%E5%8F%91)

## 文件说明
* `CQPdemo.sln` - 示例项目，可以直接在此基础上编写应用

* 您可以编译为 `com.example.democ.dll`，与 `CQPdemo/com.example.democ.json` 一起放置在酷Q的app目录下测试

* `CQPdemo/com.example.democ.json` - 样例应用的对应信息文件，包含应用的基础信息、事件列表等，请放置在酷Q的app目录下（无需使用的事件、菜单、权限请在此删除）

* `CQPdemo/cqp.h` - 酷Q SDK 头文件，通常无需修改

* `CQPdemo/CQP.lib` - CQP.dll 的动态连接 .lib 文件，便于C、C++等调用 酷Q 的方法。

## 官方网站
* [酷Q主站](https://cqp.cc)：https://cqp.cc

* [酷Q文库](https://d.cqp.me)：https://d.cqp.me

## 注意
* [Playhi](https://github.com/Playhi/cqsdk-vc) 分支是基于 [CoolQSDK](https://github.com/CoolQ/cqsdk-vc) 2016年7月14日 的master分支版本修改而来，并在之后同步更新了 2016年8月31日 的master分支更新<br>

* 相较原SDK，本分支新增了包括但可能不限于：更多注释、更多命令(`CQ_getRecord`,`CQ_sendLikeV2`,`CQ_getGroupMemberList`)、更多细节变化<br>

* 部分修改内容未必经过完全测试，欢迎使用、提议、修改、完善SDK

# English
## Introduction
* Use Visual C++ to write CoolQ Apps.

## Status
* Appveyor：<a href="https://ci.appveyor.com/project/Playhi/cqsdk-vc" target="_blank"><img src="https://ci.appveyor.com/api/projects/status/github/playhi/cqsdk-vc?branch=playhi"></a>

## Tutorials
* Please visit [https://d.cqp.me/Pro/开发](https://d.cqp.me/Pro/%E5%BC%80%E5%8F%91)

## Instruction
* `CQPdemo.sln` - Example Project,you can write apps on this basis.

* You can build the project to `com.example.democ.dll`,and test with  `CQPdemo/com.example.democ.json` under the CoolQ APP folder.

* `CQPdemo/com.example.democ.json` - The information file,includes the basic information and events list,etc.Please put it under the CoolQ APP folder with `com.example.democ.dll` (If some events,menus,permissions are not needed,please delete it).

* `CQPdemo/cqp.h` - CoolQ SDK header files,generally do not need modify.

* `CQPdemo/CQP.lib` - The static link library of CQP.dll,to make C and C++ call CoolQ more easily.

## Websites
* [CoolQ Master Website](https://cqp.cc)：https://cqp.cc

* [CoolQ Docs](https://d.cqp.me)：https://d.cqp.me

## Cautions
* The branch [Playhi](https://github.com/Playhi/cqsdk-vc) is based on the master branch of [CoolQSDK](https://github.com/CoolQ/cqsdk-vc) on 2016-7-14,and has synced with the 2016-8-31 update of the master branch of CoolQSDK<br>

* Compared with the offical CoolQSDK,the branch [Playhi](https://github.com/Playhi/cqsdk-vc) added more commands(such as `CQ_getRecord`,`CQ_sendLikeV2`,`CQ_getGroupMemberList`),and more annotations,etc.<br>

* Some parts of the modified contents have not been completely tested.<br>

* Welcome you to use,suggest,modify,optimize and do more to improve the SDK.
