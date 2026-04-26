# 热点工具（初始化阶段）

这是一个最小可运行的 Python 项目骨架，用于后续开发“热点抓取 → 文章生成 → 本地保存”工具。

> 当前阶段仅完成项目初始化，不包含热点抓取和 AI 生成逻辑。

## 项目结构

```text
.
├── .env.example
├── .gitignore
├── .venv/              # 本地虚拟环境（不提交）
├── main.py
├── README.md
└── requirements.txt
```

## 这些命令要在哪里运行？

你在网页上和我对话时，我无法直接在你的 GitHub 页面上替你点按钮执行命令。
下面这些命令需要你在**终端（Terminal）**里运行，常见有两种方式：

1. **本地电脑终端（推荐）**
   - 先把仓库 clone 到本地，再在项目目录运行命令。
2. **GitHub Codespaces 终端**
   - 在仓库页面点 `Code` → `Codespaces` → 创建/打开后，在 Codespaces 自带终端运行命令。

## 快速开始

1. 创建并激活虚拟环境（如尚未创建）

```bash
python3 -m venv .venv
source .venv/bin/activate
```

2. 安装依赖

```bash
pip install -r requirements.txt
```

3. 运行

```bash
python main.py
```

预期输出：

```text
项目已初始化
```

## 环境变量

请复制示例文件并按需修改：

```bash
cp .env.example .env
```
