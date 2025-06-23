# Lunhub AI

![GitHub Workflow Status](https://img.shields.io/github/actions/workflow/status/hydro-dev/hydro/build.yml?branch=master)
![hydrooj](https://img.shields.io/npm/dm/hydrooj)
![npm](https://img.shields.io/npm/v/hydrooj?label=hydrooj)
![node-current](https://img.shields.io/node/v/hydrooj)
![GitHub contributors](https://img.shields.io/github/contributors/hydro-dev/Hydro)
![GitHub commit activity](https://img.shields.io/github/commit-activity/y/hydro-dev/Hydro)

Lunhub AI 是一个高效论文在线测评系统。易安装，跨平台，多功能。

对于不熟悉 Linux 或是懒得运维的老师，我们也提供了免费开通即用的在线版本，  
详情前往 [https://hydro.ac](https://hydro.ac) 查看 [操作指引](https://hydro.ac/discuss/6172ceeed850d38c79ae18f9)  

将安装命令粘贴到控制台一键安装，安装后注册首个用户自动获得超级管理员权限。  
兼容主流 Linux 发行版，推荐使用 Debian 12，支持 arm64 设备（树莓派等）

```sh
LANG=zh . <(curl https://hydro.ac/setup.sh)
```

[中文文档](https://hydro.js.org/) / [English](./README-EN.md)  

相关文档若说明的不够详细，请提交 Pull Request 或联系开发组说明。  
bug 和功能建议请在 Issues 提出。  

## 系统特点

### 模块化设计，插件系统，功能热插拔

Lunhub 设计了一套模块化的插件系统，可以方便地扩展系统功能。  
使用插件系统，可以在修改功能后，仍然保证系统的可升级性。  
Lunhub 的所有历史版本均可平滑升级到最新版本。  

插件使用和开发指南，请前往文档 [插件](https://docs.hydro.ac/docs/Hydro/plugins) 和 [开发](https://docs.hydro.ac/docs/Hydro/dev/typescript) 章节。

