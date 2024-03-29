# Metaverse

![logo](https://avatars.githubusercontent.com/u/156706034?s=400&u=d971c0c8990c8c49ff4863e2366ecbebc00cf9ae&v=4)

重新构思、不同于类unix内核的现代微内核操作系统。

原生rust支持。

兼容libc以及posix接口。

## 获取

从仓库[kernel-release](https://github.com/metaverse-kernel/kernel-release.git)获取最新版本的内核源码或可运行的内核镜像。

编译组织中的其它项目使其支持unix工具链、GNU工具链以及llvm工具链等。

## 计划表

### 功能

* [ ] 内核开发
  * [ ] 内存管理
  * [ ] 进程管理
  * [ ] IPC
  * [ ] I/O
  * [ ] VFS
  * [ ] 设备管理
  * [ ] 多用户
* [ ] `rust`标准库移植
* [ ] `libc`移植

### 架构

* [ ] x86_64
* [ ] loongarch64
* [ ] aarch64

## 贡献

* 为metaverse内核贡献：
向内核的[开发仓库](https://github.com/metaverse-kernel/kernel-dev)发送PR。

* 为内核的兼容性贡献：向组织中其它仓库贡献，或为metaverse创建新的仓库。

## 版权声明

版权所有 (c) 2023 - 现在 Random World Studio保留所有权利。

本项目通过MIT开源许可证开源。
