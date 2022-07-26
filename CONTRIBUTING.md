[简体中文](#简体中文) | [English](#English)

# 简体中文

## Authing 开源项目贡献

感谢您有兴趣参与 Authing 开源项目的维护。在您提交 PR 之前，请花费一些精力阅读本指南。

## 提交（Commit）信息指南

我们可以使用 [约定式提交（Conventional Commits）](http://conventionalcommits.org/)。

- 使用现在时态 ("Adds feature" 而不是 "Added feature")
- 提交标题（信息首行）不超过 72 字节
- 每次仅提交一个需求。如果你有多个需求，请多次提交。

### 模板

推荐全部使用英文。

    <类型>: 简单介绍
    <空行>
    详细介绍
    <空行>
    (可选) Resolves: <Issue #>

### 特定 包（Package） 修改模板

    <类型>[<包名称>]: 简单介绍
    <简单介绍>
    详细介绍
    <空行>
    (可选) Resolves: <Issue #>

### 类型

支持以下类型：

- `feat` 创建新需求
- `fix` 修复 Bug
- `test` 添加测试用例
- `refactor` 代码提升或重构
- `docs` 编写文档
- `release` 发布新版本
- `chore` 其他（如 升级/降级依赖）

### 示例

    docs: Updates CONTRIBUTING.md

    Updates Contributing.md with new emoji categories
    Updates Contributing.md with new template

    Resolves: #1234

### 特定 包（Package） 修改示例

    fix[authing-angular]: Fixes bad bug

    Fixes a very bad bug in authing-angular

    Resolves: #5678

### 重大更新

- 重大更改必须在提交正文部分的最开头注明。重大更改必须包含大写文本 `BREAKING CHANGE`，后跟一个冒号和一个空格。
- 必须在 `BREAKING CHANGE:` 之后提供描述，描述 函数、API 发生了什么变化。

### 重大更新示例

    feat: Allows provided config object to extend other configs

    BREAKING CHANGE: `extends` key in config file is now used for extending other config files

# English

## Contributing to Authing Open Source Repos

Thank you for your interest in contributing to Authing's Open Source Projects! Before submitting a PR, please take a moment to read over this guide.

## Commit Message Guidelines

### Git Commit Messages

We use an adapted form of [Conventional Commits](http://conventionalcommits.org/).

- Use the present tense ("Adds feature" not "Added feature")
- Limit the first line to 72 characters or less
- Add one feature per commit. If you have multiple features, have multiple commits.

### Template

    <type>: Short Description of Commit
    <BLANKLINE>
    More detailed description of commit
    <BLANKLINE>
    (Optional) Resolves: <Issue #>

### Template for specific package change

    <type>[<package-name>]: Short Description of Commit
    <BLANKLINE>
    More detailed description of commit
    <BLANKLINE>
    (Optional) Resolves: <Issue #>

### Type

Our types include:

- `feat` when creating a new feature
- `fix` when fixing a bug
- `test` when adding tests
- `refactor` when improving the format/structure of the code
- `docs` when writing docs
- `release` when pushing a new release
- `chore` others (ex: upgrading/downgrading dependencies)

### Example

    docs: Updates CONTRIBUTING.md

    Updates Contributing.md with new emoji categories
    Updates Contributing.md with new template

    Resolves: #1234

### Example for specific package change

    fix[authing-angular]: Fixes bad bug

    Fixes a very bad bug in authing-angular

    Resolves: #5678

### Breaking changes

- Breaking changes MUST be indicated at the very beginning of the body section of a commit. A breaking change MUST consist of the uppercase text `BREAKING CHANGE`, followed by a colon and a space.
- A description MUST be provided after the `BREAKING CHANGE:`, describing what has changed about the API.

### Example for a breaking change

    feat: Allows provided config object to extend other configs

    BREAKING CHANGE: `extends` key in config file is now used for extending other config files
