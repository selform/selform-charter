# Discussions 设置清单（需要手动操作）

本仓库推荐 **Discussions 优先**。`.github/DISCUSSION_TEMPLATE/` 下的文件是讨论区的「分类表单」（YAML）；只有当对应的 Discussions 分类存在时，它们才会在发帖时出现。

## 1) 添加仓库 Topics（标签）

在仓库右侧 About 中添加：
- `philosophy`
- `agency`
- `tools-for-thought`
- `ai-alignment`
- `sensemaking`
- `human-computer-interaction`
- `ethics`

## 2) 创建 / 确认 Discussions 分类

推荐分类（名称）与 slug：
- **Welcome** → `welcome`
- **Open questions** → `open-questions`
- （可选）**Principles**、**Risks**、**Meta**

如果你的分类 slug 不一致，请将 `.github/DISCUSSION_TEMPLATE/` 中对应文件改名为实际 slug（GitHub 以文件名匹配分类）。

## 3) 预置并置顶两条讨论帖

### 置顶帖 1：“Welcome to Selform: Introduce yourself & your thoughts on Agency”
- 使用 Welcome 分类表单，或直接复制粘贴 `TEMPLATES/zh/discussion-welcome.md` 的提示。

### 置顶帖 2：“Open Question: Enhancement vs. Replacement”
- 对齐问题文件：`en/questions/q-enhancement-vs-replacement.md`
- 使用 Open questions 分类表单，或复制粘贴 `TEMPLATES/zh/discussion-open-question.md`。

