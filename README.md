# watchlist

个人「关注列表」项目仓库，用于记录、整理和跟踪自己关注的内容（待补充业务说明）。

## 项目简介

- **目标**：待补充
- **核心功能**：待补充
- **技术栈**：待补充（确定后同步更新 `.gitignore` 与下方「快速开始」）

## 目录结构

```text
watchlist/
├── .editorconfig      # 编辑器统一风格
├── .gitattributes     # 换行符与二进制文件规则
├── .gitignore         # 忽略规则
├── .gitmessage        # 提交信息模板
├── LICENSE            # MIT 许可证
└── README.md          # 项目说明
```

## 快速开始

```bash
# 1. 克隆仓库
git clone https://github.com/huaxin324/watchlist.git
cd watchlist

# 2. 安装依赖（确定技术栈后补充）
# ...

# 3. 运行（确定技术栈后补充）
# ...
```

## 开发约定

### 分支

- `main`：稳定分支，只接受通过合并进入的提交。
- `feat/<name>`：新功能；`fix/<name>`：缺陷修复；`chore/<name>`：杂项维护。
- 合并前先 `git pull -r origin main`，保持线性历史。

### 提交信息

采用 [Conventional Commits](https://www.conventionalcommits.org/zh-hans/)：

```text
<type>(<scope>): <简述>

<为什么改、改了什么>
```

常见 `type`：`feat` / `fix` / `docs` / `style` / `refactor` / `test` / `chore`。

仓库已配置 `.gitmessage` 作为提交模板（`git commit` 时自动带出提示）。

### 忽略与密钥

- 依赖目录、构建产物、缓存已在 `.gitignore` 中忽略。
- **不要提交** `.env`、密钥、token、数据库文件；需要示例时只提交 `.env.example`。

## 许可证

本项目基于 [MIT](LICENSE) 许可证开源。
