<p align="center">
    <img alt="AI Engineering Interview Questions and Answers" src="https://github.com/amitshekhariitbhu/ai-engineering-interview-questions/blob/main/assets/banner.png">
</p>

### 编者注

本仓库是 [AI Engineering Interview Questions and Answers](https://github.com/amitshekhariitbhu/ai-engineering-interview-questions) 的**中文翻译版本**。

受限于本人的知识水平和语言能力，本文档大部分依靠 AI 协助翻译，同时我进行了部分词汇的语句的调整，如有任何翻译不当或可优化之处，欢迎在 Issue 或 PR 中提出，我会及时修正。
此翻译旨在帮助更多中文开发者高效准备 AI Engineer、GenAI Engineer、LLM Engineer、Agentic AI Engineer 等岗位的面试。
感谢 Amit Shekhar 提供这个高质量的开源面试题库！

**最新更新**：2026 年 4 月 9 日

# AI 工程面试问答

> 助你备战 **AI 工程**相关面试，用作速查清单。
>
> 以下问答对准备下列岗位面试均有帮助：
>
> - AI 工程师
> - 生成式人工智能应用工程师
> - 大型语言模型（LLM）工程师
> - AI 代理模型工程师
> - AI Agent 工程师
> - AI 架构师
> - AI 平台工程师
> - 应用 AI 工程师
> - MLOps 工程师
> - LLMOps 工程师

## 目录

- [必知要点](#必知要点)
- [LLM 基础](#llm-基础)
- [提示词工程（Prompt Engineering）](#prompt-engineering-1)
- [检索增强生成（RAG）](#retrieval-augmented-generation-rag-1)
- [AI 智能体与智能体系统](#ai-agents-与-agentic-systems)
- [微调与模型适配](#fine-tuning-与模型适配)
- [向量数据库与嵌入](#vector-databases-与-embeddings)
- [AI 系统设计](#ai-system-design-1)
- [LLMOps 与生产环境 AI](#llmops-与生产环境-ai)
- [评估与测试](#evaluation-与-testing)
- [AI 安全、伦理与负责任 AI](#ai-safetyethics-与-responsible-ai)
- [多模态 AI](#multi-modal-ai-1)
- [AI 基础设施与可扩展性](#ai-infrastructure-与可扩展性)
- [编码与工程实践](#coding-与工程实践)
- [行为与情境面试题](#behavioral-与情景题)

### 由 [Outcome School](https://outcomeschool.com) 创始人 **Amit Shekhar** 编撰与维护

### 关注 Amit Shekhar

- [X/Twitter](https://twitter.com/amitiitbhu)
- [LinkedIn](https://www.linkedin.com/in/amit-shekhar-iitbhu)
- [GitHub](https://github.com/amitshekhariitbhu)

### 关注 Outcome School

- [YouTube](https://youtube.com/@OutcomeSchool)
- [X/Twitter](https://x.com/outcome_school)
- [LinkedIn](https://www.linkedin.com/company/outcomeschool)
- [GitHub](http://github.com/OutcomeSchool)

## 我在 Outcome School 开设课程

- [人工智能与机器学习](https://outcomeschool.com/program/ai-and-machine-learning)

---

> **注：我们将持续更新本仓库，补充新问答。**

---

### 必知要点

- 大型语言模型（LLM）
- 检索增强生成（RAG）
- 多任务协调（MCP）
- 智能体（Agent）
- 微调（Fine-tuning）
- 量化（Quantization）

了解LLM、RAG、MCP、Agent、微调与量化，参见：[AI Engineering Explained: LLM, RAG, MCP, Agent, Fine-Tuning, Quantization](https://www.youtube.com/watch?v=lnfWvX66FUk)

### LLM 基础

- 什么是基础模型（foundation models）？它们如何改变了 AI 工程实践？
  - 答：见视频：[AI Engineering Explained: LLM, RAG, MCP, Agent, Fine-Tuning, Quantization](https://www.youtube.com/watch?v=lnfWvX66FUk)
- 什么是大语言模型（LLM）？其工作原理是什么？
  - 答：见视频：[AI Engineering Explained: LLM, RAG, MCP, Agent, Fine-Tuning, Quantization](https://www.youtube.com/watch?v=lnfWvX66FUk)
- 揭秘 ChatGPT：按下回车之后发生了什么？
  - 答：[Inside ChatGPT: What Happens After You Hit Enter](https://outcomeschool.substack.com/p/inside-chatgpt-what-happens-after)
- Transformer 架构是什么？如何工作？
  - 答：[Decoding Transformer Architecture](https://outcomeschool.com/blog/decoding-transformer-architecture)
- Transformer 架构的核心组件有哪些？
  - 答：[Decoding Transformer Architecture](https://outcomeschool.com/blog/decoding-transformer-architecture)
- LLM 中的分词（tokenization）是什么？
  - 答：[Tokenization in Large Language Models (LLMs)](https://www.youtube.com/watch?v=sK2s9I84EVI)
- 解释 BPE (字节对编码)。
  - 答：[Byte Pair Encoding](https://outcomeschool.com/blog/bpe-in-llms)
- 解释 WordPiece 与 SentencePiece。
- 什么是位置编码（positional encoding）？为何在 Transformer 中需要它？
  - 答：[Positional Embeddings in LLMs](https://outcomeschool.substack.com/p/positional-embeddings-in-llms)
- 什么是嵌入（embeddings）？
  - 答：[Embeddings in Machine Learning](https://www.youtube.com/watch?v=LedXW6xl21s)
- 解释注意力机制中的 Q、 K 与 V（查询Query / 关键字Key / 值Value）。
  - 答：[Math behind Attention - Q, K, and V](https://outcomeschool.com/blog/math-behind-attention-qkv)
- 什么是自注意力（self-attention）？它在 Transformer 中如何运作？
  - 答：[Math behind Attention - Q, K, and V](https://outcomeschool.com/blog/math-behind-attention-qkv)
- 为何在 Transformer 架构中要对点积注意力（dot product attention）按 √dₖ 缩放？
  - 答：[Math behind √dₖ Scaling Factor in Attention](https://outcomeschool.com/blog/scaling-dot-product-attention)
- 什么是因果掩码？
  - 答：[Causal Masking in Attention](https://outcomeschool.com/blog/causal-masking-in-attention)
- 什么是多头注意力机制？为何使用多个注意力头？
  - 答：[Decoding Transformer Architecture](https://outcomeschool.com/blog/decoding-transformer-architecture)
- LLM 中的上下文窗口是什么？为何重要？
  - 答：[Context Window in LLMs](https://www.linkedin.com/posts/amit-shekhar-iitbhu_the-context-window-is-the-llms-working-memory-activity-7437754426175672320-MH9c)
- 在 LLM 语境下，温度是什么？如何影响输出？
  - 答：[What is temperature in the context of LLMs?](https://x.com/amitiitbhu/status/1964990603927687493)
- 解释 Top-p 采样与 Top-k 采样，二者有何区别？
- 什么是 logits？它们在文本生成中如何被使用？
  - 答：[Understanding Logits in Machine Learning](https://x.com/amitiitbhu/status/1927927814923207146)
- Transformer 中的残差连接（skip connections）是什么？
  - 答：[Skip connections (residual connections) in Transformers](https://www.linkedin.com/posts/amit-shekhar-iitbhu_machinelearning-llm-deeplearning-share-7414239846707392512-pQdQ)
- 开源与闭源 LLM 有何区别？怎么根据实际情况进行选择？
- 仅编码器、仅解码器与 编码器–解码器 三类 Transformer 架构有何区别？
  - 答：[Decoding Transformer Architecture](https://outcomeschool.com/blog/decoding-transformer-architecture)
- KV 缓存是什么？如何加速推理（inference）？
  - 答：[What is KV Cache in LLMs?](https://outcomeschool.com/blog/kv-cache-in-llms)
- 解释自回归建模（AR模型）与掩码语言建模（MLM）的区别。
- 什么是模型蒸馏？如何与 LLM 结合使用？
- 什么是混合专家模型（MoE）？它在 Mixtral 等模型中如何工作？
  - 答：[Mixture of Experts (MoE)](https://www.linkedin.com/posts/amit-shekhar-iitbhu_mixture-of-experts-moe-is-an-architecture-activity-7439616017284292608-7IxQ)
- 稠密模型与稀疏模型有何区别？
- Flash Attention 是什么？
- 分组查询注意力 (GQA) 是什么，与多头注意力机制 (MHA) 有何不同？
- 旋转位置编码（RoPE）如何工作？为何相对可学习位置嵌入更受青睐？
- LLM 总不遵从指令，如何使其遵循结构化输出格式？
- LLM 驱动的工具在长文档上触及上下文窗口上限，如何应对？
- LLM 在不知道答案时也不承认，如何让它诚实表示「不知道」？
- LLM 生成过于冗长，如何控制回答长度？
- LLM 记住了私有训练数据并在回答中泄露出去，如何预防？
- LLM 编程助手用已弃用的库生成过时代码，如何修复？
- 分词器把重要领域术语切成无意义的子词片段，如何修复？
- 长序列生成时 Transformer 的 KV 缓存膨胀过快，如何管理内存？
  - 答：[Paged Attention in LLMs](https://outcomeschool.com/blog/paged-attention-in-llms)
- 长文档上二次复杂度的自注意力使 Transformer 显存溢出（OOM），如何扩展？
- 蒸馏得到的学生模型在教师模型能处理的复杂推理上表现不佳，如何缩小差距？
- 经人类反馈强化学习（RLHF）对齐后 LLM 更安全但在困难任务上能力下降，如何权衡对齐税？
- 经人类反馈强化学习（RLHF）训练的 LLM「刷」奖励模型分数却未真正有用，如何抑制奖励作弊？
- 聊天机器人对话多轮后丢失上下文，如何维持长对话上下文？
- 用户中途切换话题时聊天机器人表现失常，如何应对话题切换？
- 问答系统在上下文中根本没有答案时仍生成回答，如何识别无法回答的问题？
- 摘要系统臆造原文不存在的事实，如何修复？
- 文本生成长输出中重复短语，如何修复重复问题？

<h3 id="prompt-engineering-1">提示词工程（Prompt Engineering）</h3>

- 什么是提示词工程？为何对 AI 应用至关重要？
- 结合示例解释零样本、单样本与少样本提示（zero-shot / one-shot / few-shot prompting）。
  - 答：[Explain zero-shot, one-shot, and few-shot prompting with examples](https://www.linkedin.com/posts/pallavi-shekhar_llm-prompting-ai-activity-7441801012472078336-JsHr)
- 思维链（CoT）提示是什么？何时使用？
- 解释自洽性（SC）提示及其如何改进推理。
- 思维树（ToT）提示是什么？
- ReAct（推理 + 行动）提示是什么？如何工作？
- 系统提示（system prompt）是什么？如何影响模型行为？
- 如何构造提示词以获得一致的结构化输出（如 JSON、XML）？
- 什么是提示词注入？如何防范？
- LLM 中的越狱是什么？常见越狱手法有哪些？
- 如何针对成本与延迟优化提示词？
- 提示词工程与提示词调优（prompt tuning）有何区别？
- 提示词模板是什么？如何为生产环境设计？
- 如何用 LLM 处理多轮对话？
- 角色提示词（role prompting）是什么？何时有效？
- 提示链（prompt chaining）是什么？如何为复杂任务设计多段提示？
- 如何评估并迭代提示质量？
- 元提示（meta-prompts）是什么？如何用其生成提示？
- 提示词常见失效模式有哪些？以及对应的调试方法是什么？
- 如何在提示词设计中处理边界情况与对抗性输入？
- 长上下文提示中的「中间迷失」问题是什么？
- 输出解析器是什么？在生产应用为何需要它们？
- 如何有效进行多语言提示？
- 少样本提示在相似输入上结果不稳定，如何稳住效果？
- LLM 分类系统对提示措辞过于敏感，如何降低提示敏感度？
- 聊天机器人的系统提示词含有私有业务逻辑却被用户套取，如何预防？
- LLM 智能体易受针对可窥见系统提示的注入攻击，如何防御？
- 思维链提示未提升 LLM 在推理任务上的准确率，应如何改进？
- AI 系统在英文下可用但在其他语言失败，如何增强多语言支持？
- 英文上的零样本跨语言迁移在其他语言上失败，如何修复？

<h3 id="retrieval-augmented-generation-rag-1">检索增强生成（RAG）</h3>

- 什么是检索增强生成（RAG）？为何重要？
  - 答：见视频：[AI Engineering Explained: LLM, RAG, MCP, Agent, Fine-Tuning, Quantization](https://www.youtube.com/watch?v=lnfWvX66FUk)
- 解释基本 RAG 系统的架构。
  - 答：见视频：[AI Engineering Explained: LLM, RAG, MCP, Agent, Fine-Tuning, Quantization](https://www.youtube.com/watch?v=lnfWvX66FUk)
- RAG 管道的关键组件有哪些？
  - 答：见视频：[AI Engineering Explained: LLM, RAG, MCP, Agent, Fine-Tuning, Quantization](https://www.youtube.com/watch?v=lnfWvX66FUk)
- 文本切块策略有哪些？如何选择合适的块大小？
- 比较固定长度切块、语义切块与递归切块。
- 嵌入模型是什么？如何把文本转为向量？
- 如何为 RAG 系统选择嵌入模型？
- 解释 Agentic RAG。
  - 答：[Agentic RAG](https://x.com/amitiitbhu/status/2035942587069304975)
- 混合检索是什么？为何优于纯向量检索？
- 重排序是什么？如何提升 RAG 检索质量？
- 如何在 RAG 中处理多文档与多跳问答？
- RAG 系统中的「中间迷失」问题是什么？
- 如何评估 RAG 系统？解释忠实度、相关性以及上下文精确率/召回率。
- 解释 Self-RAG：模型如何决定何时检索？
- 图 RAG（Graph RAG）是什么？相对传统 RAG 何时采用？
- 如何在 RAG 流水线中处理结构化数据（表格、SQL 数据库）？
- RAG 系统常见失效模式有哪些？如何调试？
- 如何处理文档更新并在 RAG 系统中保持内容时效？
- 如何在生产环境中为 RAG 优化延迟？
- 元数据过滤在 RAG 系统中起何作用？
- 比较 RAG 与微调，何时各用其一？
  - 答：见视频：[AI Engineering Explained: LLM, RAG, MCP, Agent, Fine-Tuning, Quantization](https://www.youtube.com/watch?v=lnfWvX66FUk)
- RAG 中的查询改写是什么（HyDE、查询分解、step-back prompting 等）？
- 如何在 RAG 中实现引用与来源归属？
- 如何将 RAG 系统扩展到数百万文档？
- 父子分段模式是什么？如何改进检索效果？
- RAG 系统明明上下文正确仍出现幻觉，如何修复？
- 切块重叠导致结果冗余，如何降低冗余？
- 知识库很大时 RAG 检索过慢，如何加速？
- RAG 系统返回重复结果，如何去重？
- RAG 系统需对内部文档做按用户访问控制，如何实现？
- RAG 系统在领域行话上表现不佳，如何修复？
- 纯文本 RAG 需支持图像与表格，如何扩展？
- RAG 知识库频繁更新且需版本管理，如何管理？
- RAG 在需综合多条事实的多跳问题上失败，如何修复？
- 企业 RAG 对不同来源文档给出矛盾答案，如何消解冲突？
- 知识库已演进 RAG 仍返回陈旧答案，如何保持答案时效？
- RAG 在含表格与版式的 PDF 上表现差，如何改进 PDF 解析？

<h3 id="ai-agents-与-agentic-systems">AI 智能体与智能体系统</h3>

- 什么是 AI 智能体（agent）？与单次调用 LLM 有何不同？
  - 答：见视频：[AI Engineering Explained: LLM, RAG, MCP, Agent, Fine-Tuning, Quantization](https://www.youtube.com/watch?v=lnfWvX66FUk)
- AI 中的 Harness Engineering（行业常保留英文；原文博文标题）
  - 答：[Harness Engineering in AI](https://outcomeschool.com/blog/harness-engineering-in-ai)
- 解释 ReAct（推理 + 行动）智能体架构。
- 计划–执行（Plan-and-Execute）智能体模式是什么？
- LLM 中的工具调用（function calling）是什么？如何赋能智能体？
  - 答：见视频：[AI Engineering Explained: LLM, RAG, MCP, Agent, Fine-Tuning, Quantization](https://www.youtube.com/watch?v=lnfWvX66FUk)
- 如何为 AI 智能体设计与定义工具？
  - 答：见视频：[AI Engineering Explained: LLM, RAG, MCP, Agent, Fine-Tuning, Quantization](https://www.youtube.com/watch?v=lnfWvX66FUk)
- 单智能体与多智能体系统有何区别？
- 模型上下文协议（MCP）是什么？如何标准化工具集成？
  - 答：见视频：[AI Engineering Explained: LLM, RAG, MCP, Agent, Fine-Tuning, Quantization](https://www.youtube.com/watch?v=lnfWvX66FUk)
- 智能体记忆有哪些类型（短期、长期、情景）？
- 如何处理智能体故障并实现错误恢复？
- 智能体循环是什么？如何决定何时停止？
- 如何评估与测试 AI 智能体？
- 智能体系统有哪些安全风险？如何缓解？
- 反应式与主动式智能体有何区别？
- 如何在长时间运行的智能体工作流中管理 token 消耗与成本？
- 人在回路（HITL）模式是什么？何时需要？
- 如何为 AI 智能体设置护栏，防止有害动作？
- 智能体反思（reflection）是什么？如何提升智能体表现？
- 代码生成智能体与工具调用智能体有何区别？
- 如何在智能体系统中处理多模态输入与输出？
- 如何在复杂智能体工作流中实现状态管理？
- 如何构建带升级逻辑的客服智能体？
- 智能体编排（orchestration）是什么？如何实现？
- 如何在沙箱环境中安全构建代码执行智能体？
- AI 智能体陷入死循环，如何检测并打破循环？
  - 答：[Fix an infinite loop in an AI agent](https://www.linkedin.com/posts/pallavi-shekhar_ai-aiagents-machinelearning-share-7440257380707364864-5Ycc)
- AI 智能体从不同工具得到冲突答案，如何调和？
- AI 智能体每项任务消耗 token 过多，如何降低消耗？
  - 答：[How would you reduce the token consumption?](https://www.linkedin.com/posts/pallavi-shekhar_ai-aiagents-machinelearning-activity-7439550125015994368-LTmE)
- AI 智能体屡屡突破单项任务预算，如何强制执行预算上限？
- AI 智能体对工具能力产生幻觉并传入错误入参，如何修复？
- AI 智能体误删生产数据库，如何预防不可逆操作？
- AI 智能体虽有诸多工具却总选错，如何改进工具选择？
- AI 智能体完成任务耗时过长，如何提速？
- LLM 选对了工具却解析错参数，如何修复参数抽取？

<h3 id="fine-tuning-与模型适配">微调（Fine-Tuning）与模型适配</h3>

- 什么是模型微调？何时应对 LLM 进行微调？
  - 答：见视频：[AI Engineering Explained: LLM, RAG, MCP, Agent, Fine-Tuning, Quantization](https://www.youtube.com/watch?v=lnfWvX66FUk)
- 解释全量微调与参数高效微调（PEFT）的区别。
  - 答：见视频：[AI Engineering Explained: LLM, RAG, MCP, Agent, Fine-Tuning, Quantization](https://www.youtube.com/watch?v=lnfWvX66FUk)
- LoRA (Low-Rank Adaptation) 是什么，如何工作？
  - 答：见视频：[AI Engineering Explained: LLM, RAG, MCP, Agent, Fine-Tuning, Quantization](https://www.youtube.com/watch?v=lnfWvX66FUk)
- QLoRA 是什么？如何在消费级硬件上实现微调？
  - 答：见视频：[AI Engineering Explained: LLM, RAG, MCP, Agent, Fine-Tuning, Quantization](https://www.youtube.com/watch?v=lnfWvX66FUk)
- 解释前缀调优（Prefix Tuning）与提示调优（Prompt Tuning），它们与 LoRA 有何不同？
- 基于适配器（adapter）的微调是什么？
  - 答：见视频：[AI Engineering Explained: LLM, RAG, MCP, Agent, Fine-Tuning, Quantization](https://www.youtube.com/watch?v=lnfWvX66FUk)
- RLHF（基于人类反馈的强化学习）是什么？如何用于对齐（align）LLM？
- 指令微调是什么？为何对对话模型重要？
- 如何为 LLM 微调准备数据集？
- 灾难性遗忘是什么？微调期间如何预防？
- 何时在微调、RAG 与提示工程之间做选择？
- 如何评估微调后模型的性能？
- 合成数据生成是什么？如何用于微调？
- 微调的关键超参数有哪些（学习率、训练轮数、批大小、LoRA 秩等）？
- 如何针对特定领域（法律、医疗、金融）微调模型？
- 持续预训练是什么？何时使用？
- 如何合并多个 LoRA 适配器？
- SFT（监督微调）与对齐训练有何区别？
- RLAIF（基于 AI 反馈的强化学习）是什么？与 RLHF 有何不同？
- 微调中的知识蒸馏是什么？法律层面需注意什么？
- 微调后的 LLM 因训练数据质量问题输出事实错误，如何修复？
- 为领域助手在 LoRA 与全量微调之间如何抉择？
- 微调模型逐字背诵训练数据而非学到泛化模式，如何缓解过拟合？
- 领域专用微调后 LLM 丧失通用能力，如何缓解灾难性遗忘？
- RLHF 偏好数据标注者一致性低，如何保证数据质量？

<h3 id="vector-databases-与-embeddings">向量数据库与嵌入（Embeddings）</h3>

- 在 AI 工程语境下，嵌入（embeddings）是什么？
  - 答：[Embeddings in Machine Learning](https://www.youtube.com/watch?v=LedXW6xl21s)
- 嵌入模型如何将文本转为向量？
- 稀疏与稠密嵌入有何区别？
- 解释向量检索中的余弦相似度、点积与欧氏距离。
- 向量数据库是什么？与传统数据库有何不同？
- 如何按业务场景选择合适的嵌入模型？
- 嵌入维度是什么？如何影响性能（效果）和成本？
- 嵌入模型更新时如何处理嵌入漂移（embedding drift）？
- 多模态嵌入是什么？如何生成？
- 如何在向量数据库中为多租户数据建索引与查询？
- 嵌入的量化（quantization）是什么？如何降低存储成本？
- 如何对嵌入模型做基准测试并评估质量？
- 元数据在向量数据库中起何作用？
- 如何应对数十亿向量规模的大规模向量检索？
- 混合检索（关键词检索与向量检索结合）是什么？
- 如何针对特定领域微调嵌入模型？
- RAG 所用向量数据库内存占用过高，如何降低？
- 向量数据库无法扩展到数百万条嵌入，如何消除瓶颈？
- 新嵌入模型与生产环境既有向量维度不一致，如何处理不匹配？
- 向量检索相似度很高却返回无关结果，如何修复？
- 部署新嵌入模型后检索质量骤降，如何应对嵌入漂移？
- 语义检索在短查询上失败，如何改进？

<h3 id="ai-system-design-1">AI 系统设计（AI System Design）</h3>

- 设计 AI 驱动的客服聊天机器人。
- 设计面向企业使用的文档问答系统。
- 设计代码生成与代码审查系统。
- 设计基于 AI 的内容审核系统。
- 设计实时 AI 推荐系统。
- 设计多模态检索系统（文本、图像、视频）。
- 设计 AI 驱动的邮件助手。
- 设计基于 AI 的医学诊断辅助。
- 设计由 LLM 驱动的欺诈检测系统。
- 设计从非结构化文档中进行 AI 驱动的数据抽取流水线。
- 设计个性化学习助手。
- 设计自动化代码迁移的 AI 系统。
- 设计 AI 驱动的法律文档审查系统。
- 设计跨会话具备记忆的对话式 AI 系统。
- 如何在 AI 系统中权衡延迟与质量？
- 如何为 LLM 应用实现缓存策略？
- 如何为 AI API 设计限流与成本管理？
- 如何为 AI 系统处理故障转移与回退策略？
- 如何设计高可用与容错的 AI 系统？
- 如何设计在模型不可用时尚能优雅降级的 AI 系统？
- 多区域部署的 AI 系统需考虑哪些要点？
- 为电商平台设计 AI 驱动的搜索引擎。
- 设计用于在组织内管理 LLM 访问的 AI 网关/代理。
- 如何设计能处理多源冲突信息的 RAG 系统？
- 如何为 AI 系统做容量规划？
- 设计多租户 AI 聊天平台，使每个企业获得定制机器人。
- 设计每日处理数千场会议的 AI 会议摘要系统。
- 设计优先排序、避免打扰的 AI 通知系统。
- 设计面向云基础设施的 AI 异常检测系统。
- 设计面向金融机构的 AI 文档处理流水线。
- 设计 AI 动态定价引擎。
- 设计每周处理 10 万份申请的 AI 简历筛选系统。
- 设计 AI 语音助手架构。
- 设计多智能体工作流，使智能体协作完成复杂任务。
- 设计面向并发音频流的实时 AI 转写系统。
- 设计 AI 驱动的直播内容审核系统。

### LLMOps 与生产环境 AI

- 从创意到生产，阐述 AI 产品生命周期。
- LLMOps 是什么？与传统 MLOps 有何区别？
- 如何在生产环境部署与服务（serve）LLM？
- 模型量化是什么？
  - 答：见视频：[AI Engineering Explained: LLM, RAG, MCP, Agent, Fine-Tuning, Quantization](https://www.youtube.com/watch?v=lnfWvX66FUk)
- 如何在生产环境监控 LLM 应用？
- LLM 可观测性是什么？
- LLM 的护栏（guardrails）是什么？如何实现？
- 如何为 AI 输出实现内容过滤？
- 如何估算生产环境中 AI 驱动功能的运行成本？
- 如何在生产环境优化 LLM 推理成本？
- 如何为 LLM 系统实现 A/B 测试？
- AI 应用的持续集成/持续部署（CI/CD）是什么？与传统 CI/CD 有何不同？
- 如何在生产环境对提示做版本管理？
- 模型版本管理是什么？如何处理模型回滚？
- 如何为 LLM API 实现限流与节流？
- 如何在不停机的情况下处理模型更新与迁移？
- 特性开关（feature flags）在 AI 部署中起何作用？
- 如何为 LLM 应用实现日志与链路追踪？
- 如何处理 LLM 输入与输出中的 PII 与敏感数据？
- LLM API 管理中的网关模式是什么？
- 如何为实时 AI 应用实现流式响应？
- 生产级 AI 系统的关键 SLA 与指标有哪些（延迟、吞吐、可用性等）？
- 云上与端侧模型部署的权衡（Cloud vs on-device）。
  - 答：[Cloud vs On-Device Model Deployment](https://x.com/outcome_school/status/1965643330076991621)
- 当主模型不可用或触发速率限制时，如何实现回退策略？
- 如何在生产环境可靠地从 LLM 获得结构化输出？
- 如何在生产环境高效处理长上下文（上下文压缩、前缀缓存等）？
- 语义路由是什么？如何在多模型系统中实现？
- 如何在 LLM 应用中安全管理机密凭据与 API 密钥？
- 高峰时段 LLM API 延迟飙升，如何稳住？
- 生产环境 LLM 成本过高，如何在尽量不大伤质量的前提下降本？
- 高峰时段应用触发 LLM 提供商限流，如何应对？
- 应用依赖单一 LLM 提供商，如何无停机切换提供商？
- AI 系统每秒百级请求尚可，五千级即崩溃，如何扩展以应对并发？
- 流量尖峰拖垮 AI 系统，如何应对峰值流量？
- 单一 LLM 提供商故障导致全系统宕机，如何消除单点故障？
- 多 LLM 流水线在链中某一模型故障时整体失败，如何应对编排故障？
- AI 流水线对哪一步失败缺乏可见性，如何增强可观测性？
- 对 LLM 量化后准确率大幅下滑，如何尽量减小量化损失？
- 单个失效的 AI 组件可拖垮整个平台，如何设计优雅降级？

<h3 id="evaluation-与-testing">评估与测试（Evaluation）</h3>

- AI 应用的评估驱动开发是什么？
- 如何评估 LLM 输出？常用哪些指标？
- 解释 BLEU、ROUGE 与 BERTScore，何时各用其一？
- G-Eval 是什么？如何用 LLM 做评估？
- 以 LLM 为裁判的评估是什么？局限有哪些？
- 如何对 AI 系统开展人工评估？
- 红队测试（red teaming）是什么？如何对 LLM 应用组织红队？
- 如何检测并度量 LLM 输出中的幻觉？
- AI 系统的对抗性测试是什么？
- 如何为 AI 应用构建回归测试套件？
- 基准套件（MMLU、HumanEval、GSM8K 等）是什么？如何解读？
- 如何端到端评估 RAG 系统？
- 如何评估 AI 智能体的质量？
- AI 系统的离线评估与线上评估有何区别？
- 如何度量 LLM 输出的事实一致性？
- 如何评估多轮对话质量？
- 黄金数据集在 AI 评估中起何作用？
- 如何为生产级 AI 系统实现持续评估？
- 如何评估 AI 模型输出中的偏见？
- 如何用统计上严谨的方式比较两个模型或两套提示？
- 如何评估 LLM 应用在输入扰动下的鲁棒性？
- 评估传统机器学习与 LLM 应用的关键差异有哪些？
- 如何从零为新 LLM 应用搭建评估框架？
- 模型通过一项公平性指标却未通过另一项，如何处理冲突的审计结果？
- 部署时模型尚属公平，半年后却出现偏见，如何持续监控？
- 外部审计无法复现模型结果，如何保证审计可复现性？
- 上线前如何组织针对 LLM 聊天机器人的红队演练？
- 如何对多模态模型做红队，使仅文本的安全测试能覆盖跨模态攻击？

<h3 id="ai-safetyethics-与-responsible-ai">AI 安全、伦理与负责任 AI</h3>

- LLM 中的幻觉是什么？如何缓解？
- 提示注入是什么？有哪些类型（直接、间接）？
- 如何为 AI 系统实现输入与输出护栏？
- AI 对齐（alignment）是什么？为何重要？
- 如何检测并缓解 AI 系统中的偏见？
- 构建 AI 应用时关键的数据隐私考量有哪些（GDPR、CCPA 等）？
- 如何处理 LLM 输入与输出中的 PII？
- AI 中的可解释性（explainability）是什么？为何重要？
- 可诠释性（interpretability）与可解释性（explainability）有何区别？
- 如何在 AI 驱动应用中与用户建立信任？
- 针对 AI 系统的对抗攻击有哪些？如何防御？
- 数据投毒是什么？对 AI 模型有何影响？
- 如何为 AI 生成内容实现内容安全过滤？
- 负责任 AI 是什么？有哪些实施框架？
- 如何处理 AI 生成内容的版权与知识产权问题？
- 《欧盟人工智能法》（EU AI Act）是什么？对 AI 工程有何影响？
- 如何为 AI 决策实现审计轨迹与日志？
- 模型卡（model card）文档是什么？为何重要？
- 如何在生产环境应对 AI 系统的滥用？
- 差分隐私是什么？如何在模型训练中应用？
- 如何设计 AI 事件响应预案？
- NIST《人工智能风险管理框架》（AI RMF）是什么？
- 医疗聊天机器人给出了不应给出的医学诊断，如何加强安全护栏？
- AI 系统逐字复现版权材料，如何预防？
- 简历筛选 AI 在工程岗位对女性候选人拒率更高，如何修复性别偏见？
- 模型分性别与分种族的偏见检查均通过，却在交叉群体上失败，如何处理？
- AI 拒绝贷款，客户依 GDPR 要求解释，如何提供？
- 用户行使被遗忘权，但其数据已进入模型权重，如何合规？
- EU AI Act 可能将系统归为高风险，如何合规？
- 差分隐私模型准确率显著下降，如何平衡隐私与效用？
- 恶意参与者在污染联邦学习模型，如何防御？
- 招聘模型使用受保护属性的代理特征，如何消除代理歧视？
- 预测模型造成有偏结果的反馈回路，如何打破？
- AI 生成假新闻图像，如何为 AI 生成内容加水印？
- AI 拒绝服务且用户无法申诉，如何设计申诉流程？
- 审计方询问六个月前 AI 为何拒绝某请求却无日志，如何建设审计轨迹？
- 已去除 PII，用户仍能从匿名数据被重新识别，如何预防再识别？
- 开源仓库中的预训练模型可能含隐蔽后门，如何检测？
- LLM 训练数据遭对手故意投毒，如何应对？
- AI 心理健康聊天机器人向危机用户给出有害建议，如何减轻伤害？
- AI 系统导致错误关键决策，如何开展无事后追责的事后分析（blameless post-mortem）？
- 放射科医生在 98% 病例中同意 AI，即使 AI 错误亦然，如何防止过度依赖 AI？
- 内容审核将其他地区的正常文化表达误判为冒犯如何进行跨文化适配？
- AI 训练产生大量碳排放，如何降低环境影响？

<h3 id="multi-modal-ai-1">多模态 AI（Multi-Modal AI）</h3>

- 多模态 AI 模型是什么？如何处理不同类型数据？
- 视觉–语言模型如何处理图像？
- CLIP 如何工作？对多模态 AI 为何重要？
- 多模态模型的关键架构有哪些？
- 扩散模型（Stable Diffusion、DALL·E、Flux 等）如何进行图像生成？
- 语音合成（TTS）是什么？常用哪些模型？
- 语音转文字（如 Whisper）如何工作？
- 多模态 RAG 是什么？与纯文本 RAG 有何不同？
- 如何构建同时处理图像与文本的系统？
- 多模态嵌入是什么？如何用于跨模态检索？
- 如何评估多模态 AI 系统？
- 实时多模态 AI 处理有哪些挑战？
- 如何用 AI 做视频理解？
- 视觉问答（VQA）是什么？
- 文档理解是什么？模型如何解析带版式的文档？
- 如何微调视觉–语言模型？
- 生产环境中多模态 AI 的延迟与成本考量有哪些？
- 如何处理多模态内容审核？
- 文生视频是什么？当前业界前沿思路有哪些？
- 解释多模态融合：早期融合（Early Fusion）与晚期融合（Late Fusion）。
- 视觉–语言模型生成与事实不符的图像描述，如何修复？
- 视觉语言模型（VLM）能答单图问题却在多页文档上失败，如何修复？
- 多模态 LLM 忽略图像、仅凭文本生成描述，如何修复？
- 扩散模型忽略文本提示中的细粒度控制，如何提升可控性？
- 扩散模型生成锐利但重复的图像，如何平衡质量与多样性？
- 扩散模型每张图采样耗时过长，如何加速采样？

<h3 id="ai-infrastructure-与可扩展性">AI 基础设施与可扩展性</h3>

- LLM 优化技巧（原文标题：LLM optimization techniques）
  - 答：[LLM optimization techniques](https://www.linkedin.com/posts/pallavi-shekhar_5-llm-optimization-techniques-lets-understand-activity-7442067281532325888-4aOS)
- 如何为 LLM 推理选择 GPU？
- 分布式训练中模型并行与数据并行有何区别？
- 张量并行是什么？如何帮助大模型服务（serving）？
- 流水线并行是什么？
- 连续批处理如何提升 LLM 推理吞吐？
- 推测解码是什么？如何加速推理？
- KV 缓存是什么？如何为其管理内存？
  - 答：[What is KV Cache in LLMs?](https://outcomeschool.com/blog/kv-cache-in-llms)
- 分页注意力（Paged Attention）是什么？
  - 答：[Paged Attention in LLMs](https://outcomeschool.com/blog/paged-attention-in-llms)
- 如何为边侧与移动端部署优化推理？
- 模型量化（INT8、INT4、FP16、BF16 等）是什么？如何影响效果（质量）？
  - 答：见视频：[AI Engineering Explained: LLM, RAG, MCP, Agent, Fine-Tuning, Quantization](https://www.youtube.com/watch?v=lnfWvX66FUk)
- 如何为 AI 负载实现自动扩缩容？
- 负载均衡在 AI 服务基础设施中起何作用？
- 如何管理 GPU 显存以服务多个模型？
- 模型分片是什么？何时使用？
- 如何为 AI 服务实现请求排队与优先级调度？
- 自托管与基于 API 的 AI 推理之间如何权衡成本？
- 如何应对无服务器 AI 部署的冷启动延迟？
- 如何实现模型缓存以减少重复计算？
- 同步推理与异步推理有何区别？何时各用其一？
- FSDP（完全分片数据并行）是什么？与 DeepSpeed ZeRO 有何不同？
- 如何在生产环境监控与剖析 LLM 推理（首 token 延迟、token 间隔延迟、GPU 利用率等）？
- 基础设施层面的模型路由是什么？如何按复杂度与成本路由请求？

<h3 id="coding-与工程实践">编码与工程实践</h3>

- 使用嵌入模型与向量数据库实现基本 RAG 流水线。
- 构建带工具调用的简单 AI 智能体（如计算器、网页搜索）。
- 使用嵌入与余弦相似度实现语义检索。
- 编写不同文本切块策略的代码（固定长度、递归、语义）。
- 实现带变量替换的提示模板系统。
- 使用「LLM 作裁判」构建 LLM 输出评估流水线。
- 为 LLM API 实现流式响应。
- 从零实现简单的向量相似度检索。
- 为聊天机器人实现会话记忆（滑动窗口、摘要、缓冲等）。
- 编写检测并处理 LLM 输出幻觉的代码。
- 为 LLM API 调用实现带指数退避的重试机制。
- 为 LLM API 编写函数调用（工具使用）处理器。
- 为搜索结果实现简单重排器。
- 构建能从 PDF 抽取文本并切块的基础文档解析器。
- 从零实现余弦相似度、点积与欧氏距离函数。
- 编写 token 计数与上下文窗口管理的代码。
- 构建简单的提示版本管理系统。
- 为 LLM 回答实现缓存层。
- 为 LLM 查询实现语义缓存（对语义相近的问题复用回答）。
- 编写检测用户输入中提示注入尝试的代码。
- 实现 LLM 输出护栏，检查离题回答与 PII 泄露。
- 构建多智能体系统，由智能体分工协作完成同一任务。

<h3 id="behavioral-与情景题">行为面试与情景题</h3>

- AI 工程（AI Engineering）是什么？与机器学习工程有何不同？
- 如何判断一个问题适合用 AI 还是传统软件解决？
- 如何度量 AI 功能的 投资回报率（ROI）？
- AI 系统出现幻觉，如何应对？
- 如何在 LLM API 与自托管开源模型之间抉择？
- 如何管理 AI 项目中相关方的预期？
- 描述你调试性能不佳的 RAG 系统的方法。
- 如何在快速发展的 AI 领域保持最新前沿？
- 如何在 AI 系统中平衡创新性与可靠性？
- 讲述你参与过的一个有挑战的 AI 项目：问题是什么？采取了何种方法？做了哪些权衡？结果如何？
- 当 AI 模型在生产环境中生成带有偏见或有害内容时，你将如何应对？
- AI 消耗超预算时，你如何从成本角度优化？
- 描述一次必须在模型准确率与延迟之间取舍的经历，你如何决策？
- 如果 AI 系统随时间推移而性能下降，你会如何处理这种情况？
- 如何向不懂技术的甲方说明 AI 的局限性？
- 标注数据有限时，你会如何构建 AI 功能？
- 描述你在 AI 项目中与跨职能团队协作的经验。
- 未来三到五年，你认为 AI 工程将走向何方？
- 你为何对这份 AI 岗位感兴趣？
- 你的上级希望上线一个在边界案例中幻觉率达 15% 的人工智能功能。你将如何向他说明风险？
- 一位不懂技术的上级询问你的 AI 为说明无法达到 100% 的准确率。你如何解释大型语言模型（LLM）的局限性？
- 需在复杂度更高的智能体系统（基准高 15%）与更易维护的简单 RAG 流水线之间选择，你会如何选择？

### License

```
   Copyright (C) 2026 Outcome School

   Licensed under the Apache License, Version 2.0 (the "License");
   you may not use this file except in compliance with the License.
   You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

   Unless required by applicable law or agreed to in writing, software
   distributed under the License is distributed on an "AS IS" BASIS,
   WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
   See the License for the specific language governing permissions and
   limitations under the License.
```

### 许可协议

```
   版权所有 (C) 2026 Outcome School

   本文件根据 Apache 许可证第 2.0 版（以下简称“本许可”）授权；
   除非遵守本许可，否则您不得使用本文件。
   您可从以下地址获取本许可的副本：

       http://www.apache.org/licenses/LICENSE-2.0

   除非适用法律要求或经书面同意，根据本许可协议分发的软件
   均按“原样”提供，
   不附带任何形式的明示或暗示的保证或条件。
   有关本许可协议下权限和
   限制的具体条款，请参阅本许可协议。
```
