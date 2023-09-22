# 项目说明

## 项目格式

* Part1：提示词工程的基础概念 MD 文档
* Part2: 提示词技术说明 MD 文档
* Part3: 按照领域划分的提示词Case MD 文档介绍
 * 领域/岗位/工作分类/具体操作
* SUMMARY：整体项目的目录


## gitbook 

基于`gitbook`框架进行调试

下载 `gitbook` ,  `gitbook` 默认是 3.2.3 版本，此版本只能通过 `nodeJS 10.x` 编译，版本过高会报错

报错如下：

```shell
TypeError: cb.apply is not a function
```
安装流程：

```shell

# 执行下载命令

curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.0/install.sh | bash

# source 环境此终端的环境变量

source ~/.nvm/nvm.sh

# 下载 node10 版本

npm install gitbook -g

nvm install 10

nvm use 10

```

## 调试

```shell
npm install gitbook -g

# 本地调试
gitbook serve

# 编译
gitbook build

#其他命令 

gitbook -h
```