# Code Specifications

这份 code specifications 的目的是让团队成员养成良好的代码习惯，同时有助于更好的团队协作。

其他语言版本: [English](./README.md).

## 特色

这份 code specifications 包含以下两个特色：

- 本地标准化编码:
  - 我们使用了 [Editorconfig](https://editorconfig.org/) 来格式化一些基础的编码格式. 它的配置文件是 [.editorconfig](./.editorconfig) 。
  - 我们使用了 [Prettier](https://prettier.io/) 和 VSCode 编辑器的 `editor.formatOnSave` 配置，来帮助我们在编码的同时规范化我们的代码. 它的配置文件是 [.prettierrc.js](./.prettierrc.js) 。
  - 我们使用了 [ESLint](https://eslint.org/) 来与 Prettier 形成互补，进一步强化代码规范。 它的配置文件是 [.eslintrc.json](./.eslintrc.json) 。
- 待提交文件的代码风格检查:
  - 我们使用了 [husky](https://github.com/typicode/husky) ，它内部封装了 Git 钩子，方便我们在提交文件之前运行一些命令，例如 Lint, Test, 等等 。
  - 我们使用了 [lint-staged](https://github.com/okonet/lint-staged) ，它监控待提交的文件，使得我们有些命令例如 Prettier 只对待提交的文件进行操作，提升速度。

## 前提条件

因为这份 code specifications 目前非常依赖  [VSCode](https://code.visualstudio.com/) 这款编辑器 , 所以在使用时我们需要安装 VSCode 编辑器。

而且，我们也需要安装一些 VSCode 插件: [Prettier](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode) , [ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint) , [EditorConfig](https://marketplace.visualstudio.com/items?itemName=EditorConfig.EditorConfig) .

## 如何使用

你只需要把这个仓库 clone 到本地，然后进入文件夹，安装相应的依赖。

```shell
git clone https://github.com/dhucst/code-specifications.git
cd code-specifications && npm install
```

然后，你就能享受到规范的编码乐趣。

## 例子

![See examples](./assets/images/example.gif)

## 贡献

**我们期望为这份 code specifications 做出贡献，让所有人、每个人都感到愉快、享受和有教育意义。**你只需要使用以下的步骤来进行贡献：

将这份仓库 fork 到本地。

![Fork this repository](./assets/images/fork.png)

将 fork 的仓库 clone 到本地。

![Clone to your local machine](./assets/images/clone.png)

然后安装依赖，添加你的修改，然后发起一个 PR 。

```shell
git clone https://github.com/pftom/code-specifications.git
cd code-specifications && npm install
```
