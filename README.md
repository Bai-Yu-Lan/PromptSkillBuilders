# 项目介绍

![](./image/logo.svg)

## 提示词工程

欢迎来到Promptskillbuilders，此项目旨在演示如何有效地使用提示词来与自然语言处理模型合作，以生成各种类型的文本内容（以岗位分类）。本仓库提供了一系列案例，展示了如何构建有效的提示词，以及如何从模型中获得最佳结果，为各个领域角色赋能。

提示词是与自然语言处理模型互动的有效方式。它们是一种简单而强大的工具，可用于生成各种类型的文本，如文章、对话、代码片段等。以下是使用提示词工程的优势：

### 1. 简化互动

使用提示词可以简化与模型的互动过程。相比于编写复杂的API请求，您只需提供一个简单的提示词或句子，模型就能够生成相应的文本。这降低了使用门槛，使更多人能够利用这一技术。

### 2. 控制生成内容

通过选择合适的提示词，您可以更精确地控制生成的内容。您可以指导模型生成特定主题、风格或语气的文本，从而满足特定需求。

### 3. 提高创造力

提示词工程有助于激发创造力。您可以使用它来生成创意文案、故事情节、艺术作品等，为各种应用增添趣味和独特性。

## 如何使用这个仓库

此仓库 `part3` 目录下包含了多个示例案例，展示了如何构建和使用提示词来生成生产资料。您可以按照以下步骤来开始使用它：

1. 查看示例：在本仓库中浏览示例文件夹，以了解各种提示词的用法和效果。

2. 克隆仓库：使用 `git clone` 命令克隆这个仓库到本地。

3. 运行示例：按照每个示例文件夹中的说明，运行相应的代码示例。您需要设置相应的API密钥和模型配置。

4. 自定义提示词：根据您的需求自定义提示词，并查看生成的文本输出。调整提示词可以让您更好地满足特定应用场景。

## 贡献和问题反馈

我们欢迎您的贡献和问题反馈。如果您有任何改进意见、新的示例案例或发现了问题，请提交问题报告或拉取请求，以帮助我们不断改进这个项目。

## 授权

本仓库采用 `木兰开放作品许可协议许可证` 授权，详情请参阅 [LICENSE](./LICENSE) 文件。

希望这个提示词工程能够帮助您更好地理解和利用自然语言处理模型，为各种应用场景生成有趣和有用的文本内容。如果您有任何疑问或建议，请随时联系我们。

## 项目说明

### 项目目录

* Part1：提示词工程的基础概念 MD 文档
* Part2: 提示词技术说明 MD 文档
* Part3: 按照领域划分的提示词Case MD 文档介绍
 * 领域/岗位/工作分类/具体操作
* SUMMARY：整体项目的目录


### 调试

基于`gitbook`框架进行封装

首先需要下载 `gitbook` ,  `gitbook` 默认是 3.2.3 版本，此版本只能通过 `nodeJS 10.x` 编译代码，版本过高会报错：

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
nvm install 10

nvm use 10
```

## 调试

```shell
# 全局安装gitbook
npm install -g gitbook-cli  
gitbook install

# 本地调试
gitbook serve

# 编译
gitbook build

#其他命令 
gitbook -h
```