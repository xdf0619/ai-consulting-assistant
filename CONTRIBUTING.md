# Contributing Guidelines

感谢你对 **AI 管理咨询助手** 感兴趣！在开始之前，请阅读以下贡献指南，以便更好地参与我们的开发工作。

## 分支管理

我们采用 `main` + 功能分支的工作流：

1. 从 `main` 分支创建你的功能分支：
   ```bash
   git checkout -b feature/<feature-name>
   ```
2. 进行开发，并适时从 `main` 分支拉取更新保持同步。
3. 提交前请确保测试通过，遵循代码规范。
4. 提交 Pull Request，等待代码评审。

## 提交规范

请尽量将一项功能或修复拆分成清晰的小提交，并在提交信息中说明改动的原因。例如：

```
feat: 添加基于向量的检索组件

实现 document_index 模块，支持文本向量化和相似度检索。
```

更多提交信息格式可参考 [Conventional Commits](https://www.conventionalcommits.org/zh-hans/v1.0.0/)。

## 代码风格

- Python 代码请遵循 [PEP 8](https://www.python.org/dev/peps/pep-0008/)。
- JavaScript/TypeScript 代码请使用 Prettier/ESLint 标准。
- 每个模块需保持注釋和文档的同步更新。

## 问题与讨论

如果你在使用本项目时遇到问题或有改进建议，请先在 [Issues](https://github.com/xdf0619/ai-consulting-assistant/issues) 中查看是否已经有人提出。

发 Issue 时请尽量提供以下信息：

1. 问题描述以及复现步骤；
2. 所使用的系统和环境信息；
3. 日志截图或错误信息；
4. 可能的解决方案或建议。

我们会尽快与你沛通并解决问题。感谢你的耐心与支持！
