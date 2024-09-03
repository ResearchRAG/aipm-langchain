# 迁移指南

## 🚨 2023年7月28日对选定链（SQLDatabase）的重大变更警告

为了使 `langchain` 更加精简和安全，我们正将选定的链迁移到 `langchain_experimental`。
此迁移已经开始，但我们保持向后兼容直到7月28日。
在该日期，我们将从 `langchain` 中移除功能。
了解更多关于迁移动机和进度的信息，请访问[这里](https://github.com/langchain-ai/langchain/discussions/8043)。

### 迁移到 `langchain_experimental`

我们将 LangChain 的任何实验性组件或存在漏洞问题的组件迁移到 `langchain_experimental`。
本指南涵盖了如何进行迁移。

### 安装

之前：

`pip install -U langchain`

现在（仅当您想要访问实验性内容时）：

`pip install -U langchain langchain_experimental`

### `langchain.experimental` 中的内容

之前：

`from langchain.experimental import ...`

现在：

`from langchain_experimental import ...`

### PALChain

之前：

`from langchain.chains import PALChain`

现在：

`from langchain_experimental.pal_chain import PALChain`

### SQLDatabaseChain

之前：

`from langchain.chains import SQLDatabaseChain`

现在：

`from langchain_experimental.sql import SQLDatabaseChain`

或者，如果您只对使用 SQL 链的查询生成部分感兴趣，可以查看这个[SQL问答教程](https://python.langchain.com/v0.2/docs/tutorials/sql_qa/#convert-question-to-sql-query)

`from langchain.chains import create_sql_query_chain`

### Python 文件的 `load_prompt`

注意：这只适用于如果您想要将 Python 文件作为提示加载。
如果您想要加载 json/yaml 文件，无需变更。

之前：

`from langchain.prompts import load_prompt`

现在：

`from langchain_experimental.prompts import load_prompt`
