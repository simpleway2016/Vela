# Vela
## 简介
Vela是一套快速部署程序的工具（俗称CI/CD），只需要提供一个git地址，就可以自动完成编译，并自动发布到目标服务器，并且以Docker容器（非root用户）的形式运行。

## 安全性
- 代码在编译服务器或者本地编译，防止代码泄露；
- 部署程序和编译服务器一对一绑定，他人无法访问部署接口；

- Docker容器以普通用户运行，免除root权限带来的危险；