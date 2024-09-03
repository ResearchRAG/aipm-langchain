🦜️🔗 语言链

⚡ 构建具有上下文感知推理能力的应用 ⚡

[![发布说明](https://img.shields.io/github/release/langchain-ai/langchain?style=flat-square)](https://github.com/langchain-ai/langchain/releases) 
[![CI](https://github.com/langchain-ai/langchain/actions/workflows/check_diffs.yml/badge.svg)](https://github.com/langchain-ai/langchain/actions/workflows/check_diffs.yml) 
[![PyPI - 许可证](https://img.shields.io/pypi/l/langchain-core?style=flat-square)](https://opensource.org/licenses/MIT) 
[![PyPI - 下载量](https://img.shields.io/pypi/dm/langchain-core?style=flat-square)](https://pypistats.org/packages/langchain-core) 
[![GitHub 星标图](https://img.shields.io/github/stars/langchain-ai/langchain?style=flat-square)](https://star-history.com/#langchain-ai/langchain) 
[![开放问题](https://img.shields.io/github/issues-raw/langchain-ai/langchain?style=flat-square)](https://github.com/langchain-ai/langchain/issues) 
[![在 Dev Containers 中打开](https://img.shields.io/static/v1?label=Dev%20Containers&message=Open&color=blue&logo=visualstudiocode&style=flat-square)](https://vscode.dev/redirect?url=vscode://ms-vscode-remote.remote-containers/cloneInVolume?url=https://github.com/langchain-ai/langchain) 
[![在 GitHub Codespaces 中打开](https://github.com/codespaces/badge.svg)](https://codespaces.new/langchain-ai/langchain) 
[![Twitter](https://img.shields.io/twitter/url/https/twitter.com/langchainai.svg?style=social&label=关注%20@LangChainAI)](https://twitter.com/langchainai) 

寻找 JS/TS 库？请查看 [LangChain.js](https://github.com/langchain-ai/langchainjs). 

想要快速将 LangChain 应用部署到生产环境，请查看 [LangSmith](https://smith.langchain.com). 
[LangSmith](https://smith.langchain.com) 是一个统一的开发平台，用于构建、测试和监控基于大型语言模型（LLM）的应用。
填写 [此表单](https://www.langchain.com/contact-sales) 与我们的销售团队交流。

## 快速安装

使用 pip:

```bash
pip install langchain
```

使用 conda:

```bash
conda install langchain -c conda-forge
```

## 🤔 什么是 LangChain?

**LangChain** 是一个用于开发由大型语言模型（LLM）驱动的应用程序的框架。

对于这些应用，LangChain 简化了整个应用生命周期：

- **开源库**：使用 LangChain 的开源[构建模块](https://python.langchain.com/v0.2/docs/concepts#langchain-expression-language-lcel)、[组件](https://python.langchain.com/v0.2/docs/concepts) 和 [第三方集成](https://python.langchain.com/v0.2/docs/integrations/platforms/) 构建你的应用。 
  使用 [LangGraph](/docs/concepts/#langgraph) 构建具有一流流式处理和人工干预支持的状态代理。
- **产品化**：使用 [LangSmith](https://docs.smith.langchain.com/) 检查、监控和评估你的应用，以便你可以持续优化并自信地部署。
- **部署**：将你的 LangGraph 应用转化为生产就绪的 API 和助手，使用 [LangGraph Cloud](https://langchain-ai.github.io/langgraph/cloud/). 

### 开源库

- **`langchain-core`**：基础抽象和 LangChain 表达语言。
- **`langchain-community`**：第三方集成。
  - 一些集成已进一步拆分为 **合作伙伴包**，仅依赖于 **`langchain-core`**。例如 **`langchain_openai`** 和 **`langchain_anthropic`**。
- **`langchain`**：链、代理和检索策略，构成了应用的认知架构。
- **[`LangGraph`](https://langchain-ai.github.io/langgraph/)**：一个库，用于通过将步骤建模为图中的边和节点，构建健壮和状态的多角色应用。与 LangChain 无缝集成，但也可以单独使用。

### 产品化：

- **[LangSmith](https://docs.smith.langchain.com/)**：一个开发平台，让你可以调试、测试、评估并监控任何 LLM 框架上构建的链，并与 LangChain 无缝集成。

### 部署：

- **[LangGraph Cloud](https://langchain-ai.github.io/langgraph/cloud/)**：将你的 LangGraph 应用转化为生产就绪的 API 和助手。

![图示展示了 LangChain 框架的层级组织结构，显示了多层之间的相互连接部分。](docs/static/svg/langchain_stack_062024.svg "LangChain 架构概览")

## 🧱 你可以用 LangChain 构建什么？

**❓ 使用 RAG 的问答**

- [文档](https://python.langchain.com/v0.2/docs/tutorials/rag/) 
- 端到端示例：[Chat LangChain](https://chat.langchain.com) 和 [仓库](https://github.com/langchain-ai/chat-langchain) 

**🧱 提取结构化输出**

- [文档](https://python.langchain.com/v0.2/docs/tutorials/extraction/) 
- 端到端示例：[SQL Llama2 模板](https://github.com/langchain-ai/langchain-extract/) 

**🤖 聊天机器人**

- [文档](https://python.langchain.com/v0.2/docs/tutorials/chatbot/) 
- 端到端示例：[Web LangChain（网络研究聊天机器人）](https://weblangchain.vercel.app) 和 [仓库](https://github.com/langchain-ai/weblangchain) 

还有更多！前往文档的 [教程](https://python.langchain.com/v0.2/docs/tutorials/) 部分了解更多。

## 🚀 LangChain 如何提供帮助？

LangChain 库的主要价值主张包括：

1. **组件**：可组合的构建模块、工具和集成，用于与语言模型协作。无论你是否使用 LangChain 框架的其他部分，组件都是模块化且易于使用的。
2. **现成的链**：内置的组件组合，用于完成更高级的任务。

现成的链让你轻松开始。组件让你轻松自定义现有链并构建新的链。

## LangChain 表达语言 (LCEL)

LCEL 是 LangChain 的关键部分，允许你以直接、声明式的方式构建和组织处理链。它的设计目的是支持将原型直接投入生产，而无需更改任何代码。这意味着你可以使用 LCEL 设置从基本的“提示 + LLM”设置到复杂的多步骤工作流。

- **[概览](https://python.langchain.com/v0.2/docs/concepts/#langchain-expression-language-lcel)**：LCEL 及其优势
- **[接口](https://python.langchain.com/v0.2/docs/concepts/#runnable-interface)**：LCEL 对象的标准 Runnable 接口
- **[原语](https://python.langchain.com/v0.2/docs/how_to/#langchain-expression-language-lcel)**：LCEL 包含的原语更多信息
- **[备忘单](https://python.langchain.com/v0.2/docs/how_to/lcel_cheatsheet/)**：最常见使用模式的快速概览

## 组件

组件分为以下 **模块**：

**📃 模型 I/O**

这包括 [提示管理](https://python.langchain.com/v0.2/docs/concepts/#prompt-templates)、[提示优化](https://python.langchain.com/v0.2/docs/concepts/#example-selectors)、通用接口 [聊天模型](https://python.langchain.com/v0.2/docs/concepts/#chat-models) 和 [LLM](https://python.langchain.com/v0.2/docs/concepts/#llms)，以及用于处理 [模型输出](https://python.langchain.com/v0.2/docs/concepts/#output-parsers) 的常用工具。

**📚 检索**

检索增强生成涉及从各种来源 [加载数据](https://python.langchain.com/v0.2/docs/concepts/#document-loaders)、[准备数据](https://python.langchain.com/v0.2/docs/concepts/#text-splitters)，然后 [搜索（即从其中检索）](https://python.langchain.com/v0.2/docs/concepts/#retrievers) 以供生成步骤使用。

**🤖 代理**

代理允许 LLM 在完成任务时拥有自主权。代理决定采取哪些行动，然后采取该行动，观察结果，并重复直到任务完成。LangChain 提供了 [标准代理接口](https://python.langchain.com/v0.2/docs/concepts/#agents)，以及用于构建自定义代理的 [LangGraph](https://github.com/langchain-ai/langgraph)。

## 📖 文档

请查看 [这里](https://python.langchain.com) 获取完整文档，包括：

- [介绍](https://python.langchain.com/v0.2/docs/introduction/)：框架和文档结构的概览。
- [教程](https://python.langchain.com/docs/use_cases/)：如果你想构建特定的东西或者更倾向于动手学习，可以查看我们的教程。这是开始的最佳地点。
- [如何指南](https://python.langchain.com/v0.2/docs/how_to/)：回答“我该如何……？”类型的问题。这些指南是目标导向和具体的；它们旨在帮助你完成特定任务。
- [概念指南](https://python.langchain.com/v0.2/docs/concepts/)：框架关键部分的概念解释。
- [API 参考](https://api.python.langchain.com)：每个类和方法的详尽文档。

## 🌐 生态系统

- [🦜🛠️ LangSmith](https://docs.smith.langchain.com/)：追踪和评估你的语言模型应用和智能代理，帮助你从原型到生产。
- [🦜🕸️ LangGraph](https://langchain-ai.github.io/langgraph/)：使用 LLM 创建状态的、多角色应用。与 LangChain 无缝集成，但也可以单独使用。
- [🦜🏓 LangServe](https://python.langchain.com/docs/langserve)：将 LangChain 可运行和链部署为 REST API。

## 💁 贡献

作为一个快速发展领域的开源项目，我们非常欢迎贡献，无论是新功能、改进的基础设施还是更好的文档。

有关如何贡献的详细信息，请查看 [这里](https://python.langchain.com/v0.2/docs/contributing/)。

## 🌟 贡献者

[![langchain 贡献者](https://contrib.rocks/image?repo=langchain-ai/langchain&max=2000)](https://github.com/langchain-ai/langchain/graphs/contributors)
