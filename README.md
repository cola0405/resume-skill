# resume-skill

**简历.skill** — 从任意 HTML 模板风格中，快速生成专业、美观、A4 单页可打印的简历。

[English](#quick-start) | 中文

> 别再从零开始写简历了。你喜欢一个 HTML 设计风格？直接把它"翻译"成高质量简历模板。

## 预览

![](examples\example.png)
## 快速开始

```bash
# 如果你使用 Hermes Agent，可以直接加载这个 skill
# 否则手动操作：
cp templates/resume-a4-zh.html my-resume.html
# 用浏览器打开，替换 [占位符]，按 P 键打印
```

**两种用法**：

1. **直接用模板** — 复制 `templates/` 下的文件，替换占位符即可
2. **从参考风格生成** — 给 AI 一个你喜欢的 HTML 模板，它会提取设计风格并生成对应简历

## 模板特点

- 严格控制在一页 A4
- 内置 PDF 颜色保护（打印不丢色）
- 中英文双模板，风格一致
- 头像、颜色、间距均可快速调整
- 所有内容用 `[占位符]` 标注，替换即可

## 目录结构

```
resume-skill/
├── SKILL.md              # 完整使用指南（Hermes Agent skill 文档）
├── README.md             # 本文件
├── LICENSE
├── templates/
│   ├── resume-a4-zh.html # 中文 A4 简历模板
│   └── resume-a4-en.html # 英文 A4 简历模板
└── examples/
    └── resume-example-zh.html  # 填好虚拟数据的示例
```

## Quick Start

> Stop building resumes from scratch. You already have an HTML design you like — this skill turns it into a professional, A4-printable resume.

1. Copy a template from `templates/`
2. Replace all `[placeholders]` with your real info
3. Press `P` in browser to print / save as PDF

**Features**: single-page A4, PDF color protection, bilingual (ZH/EN), customizable avatar/colors/spacing.

## License

MIT
