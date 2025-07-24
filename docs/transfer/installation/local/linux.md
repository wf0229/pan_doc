# Linux 安装指南

本指南将帮助您在 Linux 系统上安装和配置 reccli-ts。

## 系统要求

安装包支持以下系统环境：

- 现代 Linux 发行版 (Ubuntu 18.04+, Debian 10+, Fedora 30+ 等)
- 至少 500MB 可用磁盘空间

## 快速安装

1. 从以下链接下载最新的 Linux 安装包：
   [reccli-ts-linux-x86_64.tar.gz](../../resources/reccli-ts-linux-x86_64.tar.gz)

2. 解压下载的压缩包到任意目录：``` tar -xzf reccli-ts-linux-x86_64.tar.gz ```

3. 进入解压后的目录并运行启动脚本：``` cd reccli-ts && ./run-linux.sh ```

4. 启动成功后，打开浏览器并访问：[http://localhost:5173](http://localhost:5173)

无需额外配置，程序会自动设置所需的环境并启动并运行 reccli-ts。

!!! question "运行脚本后弹出好多黑框框？"

      在运行 `run-linux.sh` 时，可能会弹出 2 个命令行窗口，分别是运行 reccli-ts 服务器和客户端的窗口。您可以最小化这些窗口，它们会在后台运行，但是请注意在迁移任务运行过程中**不要**关闭它们，否则 reccli-ts 将无法正常工作。等您**确认**所有迁移任务结束后，您可以关闭这些窗口来结束 reccli-ts 的运行。
---

!!! question "无图形界面系统如何使用？"

      如果您的 Linux 系统没有安装图形界面，那么 `run-linux.sh` 脚本会在后台运行 reccli-ts 服务器和客户端，脚本执行过程中会打印出它们的 PID，在**确认**完成迁移任务后，您可以通过 `pkill node` 或者 `kill <PID>` 命令来结束它们的运行。
---

!!! question "运行脚本后浏览器访问不了？"

      在运行 `run-linux.sh` 时，脚本会自动配置环境变量和依赖项，并编译该项目，因此执行时间可能会稍长，请耐心等待，直到能通过浏览器访问 [http://localhost:5173](http://localhost:5173) 界面。
---

## 手动安装

如果您希望从源代码安装或自定义构建，可以按照以下步骤进行手动安装：

### 前置条件

在开始手动安装前，请确保您的系统上已安装以下工具：

- [Git](https://git-scm.com/downloads) - 用于克隆源代码仓库
- [Node.js](https://nodejs.org/) (14.x 或更高版本) - 包含 npm 包管理器

### 安装步骤

按照以下顺序执行命令：

#### 1. 下载 reccli-ts 源代码

```bash
git clone https://github.com/Vertsineu/reccli-ts.git

cd reccli-ts
```

#### 2. 安装依赖

```bash
# 安装项目依赖
npm install
npm run client:install
```

#### 3. 构建项目

```bash
# 构建项目
npm run build
npm run client:build
```

#### 4. 启动服务器和客户端

需要打开两个命令行窗口：

命令行窗口 1（启动服务器）：

```bash
npm run server
```

命令行窗口 2（启动客户端）：

```bash
npm run client
```

#### 5. 访问应用

打开浏览器并访问：[http://localhost:5173](http://localhost:5173)

手动安装可以让您完全控制构建过程，适合开发人员或需要自定义配置的高级用户。
