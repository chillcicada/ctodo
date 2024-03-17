# cTodo

简体中文 | [English](./README.md)

> 文档: <https://ctodo.chillcicada.com/zh>

## 简介

cTodo 是一个简单的 Chrome/Edge 和 Firefox 扩展程序。

## 使用方法

您可以在[cTodo文档](https://ctodo.chillcicada.com/zh/guide)中查看此扩展程序的使用方法。

## 开发

**此存储库使用 `pnpm` 作为包管理器，要求 Node 版本 >= 18。** 请确保您已经安装和配置了 `node`，并安装并启用了 `pnpm`。

```bash
# 确保启用了 pnpm
corepack enable
# 如果您运行以下命令时出现 `pnpm: not found` 错误，您可以尝试使用下面的代码来安装 pnpm
npm install -g pnpm
```

- 克隆此存储库
- 运行 `pnpm i` 以安装依赖项
- 运行 `pnpm dev` 以在 Chrome 上启动开发服务器（这需要您已安装 Chrome）
  - 运行 `pnpm dev:firefox` 以在 Firefox 上启动开发服务器（这需要您已安装 Firefox）
- 运行 `pnpm build` 以构建 Chrome-mv3（默认）的扩展程序
  - 运行 `pnpm build:firefox` 以构建 Firefox 的扩展程序

所有输出都可以在 `.output` 文件夹中找到。

如果要进行集成测试，您需要在浏览器中启用开发者模式，并从 `.output` 文件夹内加载扩展程序。

`package.json` 文件中还可以找到更多脚本。有关此存储库的更多信息，请参阅[文档](https://ctodo.chillcicada.com/zh/design)。

## 贡献

在为此存储库做出贡献之前，请了解以下内容：[代码规范](https://ctodo.chillcicada.com/zh/principle)。

## 许可证

cTodo 使用 [MIT](https://mit-license.org) 许可发布，但 **不包括下列任意情况**：

- 您过去或者目前为清华大学信息化工作办公室或信息化技术中心工作；
- 您的项目受到清华大学的下属机构或其他任何与清华大学有关的机构的任何形式的资助或支持，**包括任何竞争性项目**。
- 您对本项目的反向链接包含或提及了作者的隐私信息（如作者的真实姓名、学校电子邮件、学生身份证或任何其他私人信息）。

如果满足以上任一条件，任何未经作者**明确**授权而使用该项目的代码的行为将被视为侵犯版权（以及作者的隐私权）。此外，如果您的行为违反第三个条件，<u>您可以在不获得许可的情况下</u>，**必须选择**移除所有相关的隐私信息**或**删除反向链接（如使用 `[cTodo](link/to/thisProject) 昵称` 或 `cTodo 真实姓名`）。

上文中的“**使用**”包括对项目的源代码或衍生品（如浏览器插件）制作拷贝、修改、重分发，无论是否用作商业用途。但安装并运行作者发布的浏览器插件的行为不受此例外约束。
