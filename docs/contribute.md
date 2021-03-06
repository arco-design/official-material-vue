`````
开发指南

# 共建物料

我们欢迎来自社区的力量一同建设 Arco 物料，阅读本文档以了解如何参与。
`````

基于 [Arco Design Vue](https://arco.design/vue) 所提供的基础组件，我们创建了这个由 Arco 官方维护的物料库。我们欢迎社区开发者共同参与到此物料的建设中来，基于 Arco Material Market 提供满足更多使用场景的物料。

# 物料范畴

此仓库的定位为可以随处使用、不与任何业务逻辑耦合的物料集合。如果你需要的新组件满足以下特点，就可以考虑将其添加为此仓库的一枚物料！

* 增强型的 Arco 基础组件，例如：带有分组功能的选择器、卡片式的单选框；
* 无业务逻辑耦合的 UI 组件，例如：用户信息卡片、页脚、图片裁剪上传；

我们不强制要求物料必须使用 `@arco-design/web-vue`，你也可以使用原生 Vue 来实现你的物料。

# 参与建设

## 技术栈

首先你需要掌握以下技能，以快速上手物料的开发：

* [Vue3](https://vuejs.org/)
* [Typescript](https://www.tslang.cn/docs/home.html)
* [Jest](https://jestjs.io)

## 开发前准备

1. 克隆仓库

```bash
git clone git@github.com:arco-design/official-material-vue.git
```

2. 初始环境

```bash
cd official-material-vue

# 仓库使用 yarn 进行包管理，如未安装 yarn 可通过 npm i yarn -g 来安装它
yarn

# 建立 NPM 软链
lerna bootstrap

# 启动 Storybook 进入开发
yarn dev
```

3. 如果你需要添加一个新物料，通过以下命令在仓库中添加一个新包：

```bash
yarn add:package your-package-name
```

开发新的物料需要了解 Arco Material Market 的运作流程，请阅读我们的 [物料指南](https://arco.design/docs/material/guide)。

# 需要新物料？

可以在 [Issue 面板](`https://github.com/arco-design/official-material-vue/issues`) 提出你所需要的物料，也欢迎你自己实现并将其加入此仓库。