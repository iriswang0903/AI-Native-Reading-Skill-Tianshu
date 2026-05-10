# GitHub 建仓指南

## 创建仓库时填写

| 字段 | 填写内容 |
|------|---------|
| **Repository name** | `ai-native-reading` |
| **Description** | `Turn any book into a cross-disciplinary knowledge network. Works with Claude, GPT, Gemini, and any long-context AI.` |
| **Public / Private** | Public |
| **Add a README** | ❌ 不勾（我们自己有） |
| **Add .gitignore** | ❌ 不勾（我们自己有） |
| **Choose a license** | ❌ 不勾（我们自己有） |

## 仓库文件结构

```
ai-native-reading/
├── README.md              ← 项目首页（中英双语）
├── LICENSE                ← MIT License
├── .gitignore             ← 忽略 epub/pdf 等大文件
├── prompt-en.md           ← 英文版完整 Prompt（复制即用）
├── prompt-zh.md           ← 中文版完整 Prompt（复制即用）
└── ai-native-reading.skill ← Claude 专用 Skill 文件
```

## 上传步骤

1. 在 GitHub 创建仓库（填写上面的信息）
2. 把 `github-repo/` 文件夹里的所有文件上传
3. 发布

## 建议添加的 Topics（标签）

在仓库 Settings → Topics 里添加：

```
ai-reading, reading-method, cross-disciplinary, prompt-engineering,
claude, gpt, gemini, non-fiction, knowledge-management, book-reading,
ai-tools, learning-method
```

## 建议的 Social Preview（封面图）

可以用我们之前做的流程图 HTML 截图作为仓库封面。在 Settings → Social preview 上传。

## About 栏（右侧边栏）

| 字段 | 内容 |
|------|------|
| **Description** | Turn any book into a cross-disciplinary knowledge network |
| **Website** | （如果有公众号文章链接可以放这里） |
| **Topics** | 见上面的标签列表 |

## 可选：Release

如果想让别人更容易下载 .skill 文件，可以创建一个 Release：
- Tag: `v1.0`
- Title: `AI-Native Reading Method v1.0`
- Description: `First release. Co-created through a complete reading of Gödel, Escher, Bach.`
- 附件：上传 `ai-native-reading.skill`
