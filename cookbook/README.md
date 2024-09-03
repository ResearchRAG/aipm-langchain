# LangChain 应用指南

构建 LangChain 应用程序的示例代码，与[主要文档](https://python.langchain.com)中的内容相比，更注重应用性和端到端的示例。

笔记本 | 描述
:- | :-
[agent_fireworks_ai_langchain_mongodb.ipynb](https://github.com/langchain-ai/langchain/tree/master/cookbook/agent_fireworks_ai_langchain_mongodb.ipynb) | 使用 MongoDB、LangChain 和 FireWorksAI 构建具有记忆功能的 AI 代理。
[mongodb-langchain-cache-memory.ipynb](https://github.com/langchain-ai/langchain/tree/master/cookbook/mongodb-langchain-cache-memory.ipynb) | 使用 MongoDB 和 LangChain 构建具有语义缓存的 RAG 应用程序。
[LLaMA2_sql_chat.ipynb](https://github.com/langchain-ai/langchain/tree/master/cookbook/LLaMA2_sql_chat.ipynb) | 构建一个与 SQL 数据库交互的聊天应用程序，使用开源语言模型（如 llama2），特别演示了包含花名册的 SQLite 数据库。
[Semi_Structured_RAG.ipynb](https://github.com/langchain-ai/langchain/tree/master/cookbook/Semi_Structured_RAG.ipynb) | 对包含文本和表格的半结构化文档执行检索增强生成（rag），使用非结构化工具进行解析，多向量检索器进行存储，并使用 lcel 实现链。
[Semi_structured_and_multi_modal_RAG.ipynb](https://github.com/langchain-ai/langchain/tree/master/cookbook/Semi_structured_and_multi_modal_RAG.ipynb) | 对包含半结构化数据和图像的文档执行检索增强生成（rag），使用非结构化工具进行解析，多向量检索器进行存储和检索，并使用 lcel 实现链。
[Semi_structured_multi_modal_RAG_LLaMA2.ipynb](https://github.com/langchain-ai/langchain/tree/master/cookbook/Semi_structured_multi_modal_RAG_LLaMA2.ipynb) | 对包含半结构化数据和图像的文档执行检索增强生成（rag），使用各种工具和方法，如非结构化工具进行解析，多向量检索器进行存储，lcel 实现链，以及像 llama2、llava 和 gpt4all 这样的开源语言模型。
[amazon_personalize_how_to.ipynb](https://github.com/langchain-ai/langchain/blob/master/cookbook/amazon_personalize_how_to.ipynb) | 从 Amazon Personalize 检索个性化推荐，并使用自定义代理构建生成性 AI 应用程序。
[analyze_document.ipynb](https://github.com/langchain-ai/langchain/tree/master/cookbook/analyze_document.ipynb) | 分析单个长文档。
[autogpt/autogpt.ipynb](https://github.com/langchain-ai/langchain/tree/master/cookbook/autogpt/autogpt.ipynb) | 使用 LangChain 原语（如 llms、prompttemplates、vectorstores、embeddings 和工具）实现 autogpt 语言模型。
[autogpt/marathon_times.ipynb](https://github.com/langchain-ai/langchain/tree/master/cookbook/autogpt/marathon_times.ipynb) | 实现 autogpt 以查找马拉松获胜时间。
[baby_agi.ipynb](https://github.com/langchain-ai/langchain/tree/master/cookbook/baby_agi.ipynb) | 实现 babyagi，一个可以根据给定目标生成和执行任务的 AI 代理，具有替换特定向量存储/模型提供商的灵活性。
[baby_agi_with_agent.ipynb](https://github.com/langchain-ai/langchain/tree/master/cookbook/baby_agi_with_agent.ipynb) | 在 babyagi 笔记本中，将执行链替换为具有工具访问权限的代理，以获得更可靠的信息。
[camel_role_playing.ipynb](https://github.com/langchain-ai/langchain/tree/master/cookbook/camel_role_playing.ipynb) | 实施骆驼框架，以在大规模语言模型中创建自主协作代理，使用角色扮演和 inception 提示引导聊天代理完成任务。
[causal_program_aided_language_model.ipynb](https://github.com/langchain-ai/langchain/tree/master/cookbook/causal_program_aided_language_model.ipynb) | 实施因果程序辅助语言（cpal）链，通过纳入因果结构来改进程序辅助语言（pal），以防止语言模型中的幻觉，特别是在处理复杂的叙事和具有嵌套依赖性的数学问题时。
[code-analysis-deeplake.ipynb](https://github.com/langchain-ai/langchain/tree/master/cookbook/code-analysis-deeplake.ipynb) | 在 gpt 和 activeloop 的 deep lake 的帮助下分析自己的代码库。
[custom_agent_with_plugin_retrieval.ipynb](https://github.com/langchain-ai/langchain/tree/master/cookbook/custom_agent_with_plugin_retrieval.ipynb) | 构建一个可以与 AI 插件交互的自定义代理，通过检索工具并在 openapi 端点周围创建自然语言包装器。
[custom_agent_with_plugin_retrieval_using_plugnplai.ipynb](https://github.com/langchain-ai/langchain/tree/master/cookbook/custom_agent_with_plugin_retrieval_using_plugnplai.ipynb) | 构建一个具有插件检索功能的自定义代理，利用 `plugnplai` 目录中的 AI 插件。
[databricks_sql_db.ipynb](https://github.com/langchain-ai/langchain/tree/master/cookbook/databricks_sql_db.ipynb) | 连接到 databricks 运行时和 databricks SQL。
[deeplake_semantic_search_over_chat.ipynb](https://github.com/langchain-ai/langchain/tree/master/cookbook/deeplake_semantic_search_over_chat.ipynb) | 使用 activeloop 的 deep lake 和 gpt4 在群聊中执行语义搜索和问答。
[elasticsearch_db_qa.ipynb](https://github.com/langchain-ai/langchain/tree/master/cookbook/elasticsearch_db_qa.ipynb) | 以自然语言与 elasticsearch 分析数据库交互，并通过 elasticsearch dsl API 构建搜索查询。
[extraction_openai_tools.ipynb](https://github.com/langchain-ai/langchain/tree/master/cookbook/extraction_openai_tools.ipynb) | 使用 OpenAI 工具进行结构化数据提取。
[forward_looking_retrieval_augmented_generation.ipynb](https://github.com/langchain-ai/langchain/tree/master/cookbook/forward_looking_retrieval_augmented_generation.ipynb) | 实施前瞻性主动检索增强生成（flare）方法，生成问题的答案，识别不确定的标记，基于这些标记生成假设性问题，并检索相关文档以继续生成答案。
[generative_agents_interactive_simulacra_of_human_behavior.ipynb](https://github.com/langchain-ai/langchain/tree/master/cookbook/generative_agents_interactive_simulacra_of_human_behavior.ipynb) | 实施一个生成性代理，模拟人类行为，基于研究论文，使用由 LangChain 检索器支持的时间加权记忆对象。
[gymnasium_agent_simulation.ipynb](https://github.com/langchain-ai/langchain/tree/master/cookbook/gymnasium_agent_simulation.ipynb) | 在像基于文本的游戏这样的模拟环境中创建简单的代理-环境交互循环，使用 gymnasium。
[hugginggpt.ipynb](https://github.com/langchain-ai/langchain/tree/master/cookbook/hugginggpt.ipynb) | 实施 hugginggpt，一个系统，通过 hugging face 将语言模型（如 chatgpt）与机器学习社区连接起来。
[hypothetical_document_embeddings.ipynb](https://github.com/langchain-ai/langchain/tree/master/cookbook/hypothetical_document_embeddings.ipynb) | 使用假设性文档嵌入（hyde）技术改进文档索引，该技术生成并嵌入对查询的假设性答案。
[learned_prompt_optimization.ipynb](https://github.com/langchain-ai/langchain/tree/master/cookbook/learned_prompt_optimization.ipynb) | 使用强化学习自动增强语言模型提示，通过注入特定术语，可以根据用户偏好个性化响应。
[llm_bash.ipynb](https://github.com/langchain-ai/langchain/tree/master/cookbook/llm_bash.ipynb) | 使用语言学习模型（llms）和 bash 进程执行简单的文件系统命令。
[llm_checker.ipynb](https://github.com/langchain-ai/langchain/tree/master/cookbook/llm_checker.ipynb) | 使用 llmcheckerchain 函数创建自检链。
[llm_math.ipynb](https://github.com/langchain-ai/langchain/tree/master/cookbook/llm_math.ipynb) | 使用语言模型和 python repls 解决复杂的文字数学问题。
[llm_summarization_checker.ipynb](https://github.com/langchain-ai/langchain/tree/master/cookbook/llm_summarization_checker.ipynb) | 检查文本摘要的准确性，可选择多次运行检查器以提高结果。
[llm_symbolic_math.ipynb](https://github.com/langchain-ai/langchain/tree/master/cookbook/llm_symbolic_math.ipynb) | 在语言学习模型（llms）和 sympy（一个用于符号数学的 python 库）的帮助下解代数方程。
[meta_prompt.ipynb](https://github.com/langchain-ai/langchain/tree/master/cookbook/meta_prompt.ipynb) | 实施元提示概念，这是一种构建自我改进代理的方法，代理可以反思自己的表现并相应地修改其指令。
[multi_modal_output_agent.ipynb](https://github.com/langchain-ai/langchain/tree/master/cookbook/multi_modal_output_agent.ipynb) | 生成多模态输出，特别是图像和文本。
[multi_modal_RAG_vdms.ipynb](https://github.com/langchain-ai/langchain/tree/master/cookbook/multi_modal_RAG_vdms.ipynb) | 在包括文本和图像的文档上执行检索增强生成（rag），使用非结构化工具进行解析，Intel 的视觉数据管理系统（VDMS）作为向量存储，并使用链。
[multi_player_dnd.ipynb](https://github.com/langchain-ai/langchain/tree/master/cookbook/multi_player_dnd.ipynb) | 模拟多玩家龙与地下城游戏，使用自定义函数确定代理的发言顺序。
[multiagent_authoritarian.ipynb](https://github.com/langchain-ai/langchain/tree/master/cookbook/multiagent_authoritarian.ipynb) | 实施一个多代理模拟，其中一个特权代理控制对话，包括决定谁发言和何时结束对话，在模拟新闻网络的背景下。
[multiagent_bidding.ipynb](https://github.com/langchain-ai/langchain/tree/master/cookbook/multiagent_bidding.ipynb) | 实施一个多代理模拟，代理出价发言，最高出价者下一个发言，通过一个虚构的总统辩论示例演示。
[myscale_vector_sql.ipynb](https://github.com/langchain-ai/langchain/tree/master/cookbook/myscale_vector_sql.ipynb) | 访问和交互 myscale 集成向量数据库，这可以增强语言模型（llm）应用程序的性能。
[openai_functions_retrieval_qa.ipynb](https://github.com/langchain-ai/langchain/tree/master/cookbook/openai_functions_retrieval_qa.ipynb) | 通过将 OpenAI 功能整合到检索管道中，在问答系统中构建结构化响应输出。
[openai_v1_cookbook.ipynb](https://github.com/langchain-ai/langchain/tree/master/cookbook/openai_v1_cookbook.ipynb) | 探索与 OpenAI Python 库 V1 版本同时发布的新功能。
[petting_zoo.ipynb](https://github.com/langchain-ai/langchain/tree/master/cookbook/petting_zoo.ipynb) | 使用 petting zoo 库和模拟环境创建多代理模拟。
[plan_and_execute_agent.ipynb](https://github.com/langchain-ai/langchain/tree/master/cookbook/plan_and_execute_agent.ipynb) | 创建计划和执行代理，通过语言模型（llm）规划任务并由单独的代理执行来实现目标。
[press_releases.ipynb](https://github.com/langchain-ai/langchain/tree/master/cookbook/press_releases.ipynb) | 检索和查询由 [Kay.ai](https://kay.ai) 提供支持的公司新闻稿数据。
[program_aided_language_model.ipynb](https://github.com/langchain-ai/langchain/tree/master/cookbook/program_aided_language_model.ipynb) | 如研究论文中所述，实现程序辅助语言模型。
[qa_citations.ipynb](https://github.com/langchain-ai/langchain/tree/master/cookbook/qa_citations.ipynb) | 获取模型引用其来源的不同方式。
[rag_upstage_layout_analysis_groundedness_check.ipynb](https://github.com/langchain-ai/langchain/tree/master/cookbook/rag_upstage_layout_analysis_groundedness_check.ipynb) | 使用 Upstage Layout Analysis 和 Groundedness Check 的端到端 RAG 示例。
[retrieval_in_sql.ipynb](https://github.com/langchain-ai/langchain/tree/master/cookbook/retrieval_in_sql.ipynb) | 使用 pgvector 在 PostgreSQL 数据库上执行检索增强生成（rag）。
[sales_agent_with_context.ipynb](https://github.com/langchain-ai/langchain/tree/master/cookbook/sales_agent_with_context.ipynb) | 实施一个具有上下文感知的 AI 销售代理，salesgpt，它可以进行自然的销售人员交谈，与其他系统集成，并使用产品知识库讨论公司的产品。
[self_query_hotel_search.ipynb](https://github.com/langchain-ai/langchain/tree/master/cookbook/self_query_hotel_search.ipynb) | 使用特定酒店推荐数据集构建具有自我查询检索的酒店房间搜索功能。
[smart_llm.ipynb](https://github.com/langchain-ai/langchain/tree/master/cookbook/smart_llm.ipynb) | 实施 smartllmchain，一个自我批评链，生成多个输出提案，批评它们以找到最佳方案，然后改进它以产生最终输出。
[tree_of_thought.ipynb](https://github.com/langchain-ai/langchain/tree/master/cookbook/tree_of_thought.ipynb) | 使用思维树技术查询大型语言模型。
[twitter-the-algorithm-analysis-deeplake.ipynb](https://github.com/langchain-ai/langchain/tree/master/cookbook/twitter-the-algorithm-analysis-deeplake.ipynb) | 在 gpt4 和 activeloop 的 deep lake 的帮助下分析 Twitter 算法源代码。
[two_agent_debate_tools.ipynb](https://github.com/langchain-ai/langchain/tree/master/cookbook/two_agent_debate_tools.ipynb) | 模拟多代理对话，代理可以利用各种工具。
[two_player_dnd.ipynb](https://github.com/langchain-ai/langchain/tree/master/cookbook/two_player_dnd.ipynb) | 模拟两位玩家的龙与地下城游戏，使用对话模拟器类协调主角和地下城主之间的对话。
[wikibase_agent.ipynb](https://github.com/langchain-ai/langchain/tree/master/cookbook/wikibase_agent.ipynb) | 创建一个简单的 wikibase 代理，利用 SPARQL 生成，在 http://wikidata.org 上进行测试。
[oracleai_demo.ipynb](https://github.com/langchain-ai/langchain/tree/master/cookbook/oracleai_demo.ipynb) | 本指南概述了如何结合 Oracle AI 向量搜索和 Langchain 实现端到端 RAG 管道，并提供逐步示例。过程包括使用 OracleDocLoader 从各种来源加载文档，使用 OracleSummary 在数据库内部或外部对它们进行摘要，并通过 OracleEmbeddings 类似地生成嵌入。它还涵盖了使用 OracleTextSplitter 的高级 Oracle 功能根据特定要求对文档进行分块，最后将这些文档存储在向量存储中以供 OracleVS 查询。
[rag-locally-on-intel-cpu.ipynb](https://github.com/langchain-ai/langchain/tree/master/cookbook/rag-locally-on-intel-cpu.ipynb) | 使用 Langchain 和开源工具在本地下载的开源模型上执行检索增强生成（RAG），并在 Intel Xeon CPU 上执行。我们展示了如何在 Llama 2 模型上应用 RAG 并使其能够回答与 Intel 2024 年第一季度收益发布相关的查询。
[visual_RAG_vdms.ipynb](https://github.com/langchain-ai/langchain/tree/master/cookbook/visual_RAG_vdms.ipynb) | 使用由开源模型生成的视频和场景描述执行视觉检索增强生成（RAG）。

