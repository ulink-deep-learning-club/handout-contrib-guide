# 讲义贡献指南

面向第一次参与 Ulink 深度学习社讲义项目（[ulink-deeplearningclub-handouts](https://github.com/ulink-deep-learning-club/ulink-deeplearningclub-handouts)）的零基础贡献指南。涵盖 GitHub 与 Git 流程、Markdown 基础、讲义项目的 MyST/Sphinx 写法、写作与代码约定，以及常见问题。

## 文件

| 文件 | 说明 |
| --- | --- |
| `contributing-for-beginners.tex` | 正文 |
| [`contributing-for-beginners.pdf`](./contributing-for-beginners.pdf) | 编译好的 PDF |
| `img/` | 文中截图，文件名以章节序号开头 |

## 编译

用 XeLaTeX 编译两遍（第二遍生成目录与交叉引用）：

```bash
xelatex contributing-for-beginners.tex
xelatex contributing-for-beginners.tex
```

需要 TeX Live（含 `ctex`、`tcolorbox`、`tikz`、`longtable` 等宏包）与中文字体 Noto Serif/Sans CJK SC。

## 内容结构

1. 项目里有什么
2. 四个词：仓库、分支、提交、PR
3. 装好工具
4. 最快的一次贡献：在网页上改一个错别字
5. 完整流程：从 Issue 到合并
6. Git 常用操作（撤销、冲突）
7. Markdown 基础
8. 讲义项目的 MyST 写法（提示框、Mermaid、公式、文献、目录树等）
9. 写作要求、代码贡献、翻译贡献
10. 提交前检查、常见问题、术语表
