# Agent Artifacts

一个用于存放和共享 AI Agent 生成文件的通用仓库。

这里可以保存 Agent 在工作过程中产生的各种文件，例如：

- 分析报告、技术文档和调研记录
- 架构图、流程图及其他图表
- 图片、演示文稿和电子表格
- 代码片段、配置文件及其他辅助文件
- 临时产物、中间结果和最终交付物

## 定位

本仓库只负责文件存储与共享，不负责管理文件背后的知识或工作流程。

- **通用**：不绑定特定 Agent、模型或开发工具。
- **开放**：不限制文件类型、格式或生成方式。
- **轻量**：不强制统一的内容格式、命名规则或元数据。
- **简单**：Agent 和用户都可以通过 GitHub 或 Git 操作文件。

文件是否长期有用、是否属于最终产物，由使用者自行决定。临时文件和中间结果同样可以存放在这里。

## 目录组织

不预设固定的目录结构，也不要求所有文件遵循统一分类。

可以根据实际使用场景自由组织文件。例如，一次任务生成的多个相关文件可以放在同一个目录中：

```text
agent-artifacts/
├── README.md
├── backend-architecture-evolution/
│   ├── architecture.md
│   ├── system-overview.svg
│   └── evolution-flow.png
└── repository-analysis/
    ├── report.md
    └── module-structure.svg
```

以上仅为示例。可以直接在仓库根目录添加文件，也可以按任务、主题或个人习惯创建目录。

## 使用方式

### 通过 Git

克隆仓库后，像普通文件目录一样添加、修改和管理文件：

```bash
git clone https://github.com/Happyileaf/agent-artifacts.git
cd agent-artifacts

git add .
git commit -m "Add generated artifacts"
git push
```

### 通过 Agent

支持 GitHub 操作的 Agent 可以在获得相应仓库权限后，直接读取、创建和更新文件，并通过分支与 Pull Request 提交变更。

### 通过 GitHub

也可以直接在 GitHub 网页端浏览、上传、下载和分享文件。

## 原则

**仓库负责存储，不负责约束 Agent 如何生成内容。**
