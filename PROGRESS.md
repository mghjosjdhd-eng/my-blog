# 项目进度 — 个人技术博客

## 当前状态：🚧 第 1 步进行中（刚创建完目录结构）

## 已完成

### 项目一：CLI 工具箱 ✅
- 仓库：https://github.com/mghjosjdhd-eng/cli-toolbox（私有）
- 4 个工具全部实现：rename、jsonfmt、stats、toc
- 21 个单元测试全部通过
- 代码审查完成，修了 12 个正确性 bug + 7 个整洁问题
- 已推送到 GitHub

### 项目二：个人博客 — 进度 5%
- [x] 选择技术栈：Astro 框架
- [x] 计划已批准（计划文件：~/.claude/plans/splendid-riding-snowglobe.md）
- [x] 检查 Node.js (v24.16.0) 和 npm (11.13.0) 可用
- [x] 创建目录结构

## 下一步（按顺序）

### 第 1 步：初始化 Astro 项目（当前步骤）
需要做：
1. 创建 `package.json`
2. `npm install astro`
3. 创建 `astro.config.mjs`
4. 创建 `.gitignore`
5. `npm run dev` 验证能在本地跑起来
6. 清理模板自带代码（如果有）

### 第 2 步：创建布局和组件
- src/layouts/Layout.astro
- src/components/Header.astro
- src/components/Footer.astro
- src/components/PostCard.astro
- src/styles/global.css

### 第 3 步：实现页面
- src/pages/index.astro（首页）
- src/pages/posts/[slug].astro（文章详情）
- src/pages/about.astro（关于页）
- src/pages/404.astro

### 第 4 步：写示例文章
- src/content/posts/hello-world.md
- src/content/posts/why-learn-programming.md

### 第 5 步：GitHub Actions 自动部署
- .github/workflows/deploy.yml

### 第 6 步：推送 + 验证上线
- git init → commit → gh repo create → push
- 启用 GitHub Pages
- 访问 https://mghjosjdhd-eng.github.io/my-blog/ 确认

## 关键信息

- GitHub 账号：mghjosjdhd-eng
- 项目路径：d:\项目\一些项目的练习\my-blog\
- 计划文件：C:\Users\MY202\.claude\plans\splendid-riding-snowglobe.md
- 项目一参考：d:\项目\一些项目的练习\cli-toolbox\
- 终端是 Git Bash，中文可能乱码但不影响功能

## 如何继续

在新对话中说：
> "继续 my-blog 项目，先读 d:\项目\一些项目的练习\my-blog\PROGRESS.md"

或者直接说：
> "帮我继续做个人博客项目，目录已经在 d:\项目\一些项目的练习\my-blog\ 了"
