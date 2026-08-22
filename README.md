<p align="center">
    <img alt="AI Engineering Interview Questions and Answers" src="https://github.com/amitshekhariitbhu/ai-engineering-interview-questions/blob/main/assets/banner.png">
</p>

# AI Engineering Interview Questions and Answers

> AI Engineering Interview Questions and Answers 1. Your Cheat Sheet For AI Engineering Interviews
>
> These interview questions and answers are helpful for roles such as:
>
> 1. AI Engineer
> 1. Gen AI Engineer
> 1. LLM Engineer
> 1. Agentic AI Engineer
> 1. AI Agent Engineer
> 1. Forward Deployed Engineer
> 1. AI Solutions Architect
> 1. AI Platform Engineer
> 1. Applied AI Engineer
> 1. MLOps Engineer
> 1. LLMOps Engineer

## Table of Contents

1. [Must Know](#must-know)
1. [LLM Fundamentals](#llm-fundamentals)
1. [Prompt Engineering](#prompt-engineering)
1. [Retrieval-Augmented Generation (RAG)](#retrieval-augmented-generation-rag)
1. [AI Agents and Agentic Systems](#ai-agents-and-agentic-systems)
1. [Fine-Tuning and Model Adaptation](#fine-tuning-and-model-adaptation)
1. [Vector Databases and Embeddings](#vector-databases-and-embeddings)
1. [AI System Design](#ai-system-design)
1. [LLMOps and Production AI](#llmops-and-production-ai)
1. [Evaluation and Testing](#evaluation-and-testing)
1. [AI Safety, Ethics, and Responsible AI](#ai-safety-ethics-and-responsible-ai)
1. [Multimodal AI](#multimodal-ai)
1. [AI Infrastructure and Scalability](#ai-infrastructure-and-scalability)
1. [Coding and Practical Implementation](#coding-and-practical-implementation)
1. [Behavioral and Scenario-Based Questions](#behavioral-and-scenario-based-questions)

### Prepared and maintained by the **Founder** of [Outcome School](https://outcomeschool.com): Amit Shekhar

### Follow Amit Shekhar

1. [X/Twitter](https://twitter.com/amitiitbhu)
1. [LinkedIn](https://www.linkedin.com/in/amit-shekhar-iitbhu)
1. [GitHub](https://github.com/amitshekhariitbhu)

### Follow Outcome School

1. [YouTube](https://youtube.com/@OutcomeSchool)
1. [X/Twitter](https://x.com/outcome_school)
1. [LinkedIn](https://www.linkedin.com/company/outcomeschool)
1. [GitHub](http://github.com/OutcomeSchool)

## I teach at Outcome School

1. [AI and Machine Learning](https://outcomeschool.com/program/ai-and-machine-learning)

---

> **Note: We will keep updating this with new questions and answers.**

---

### Must Know

1. LLM
1. RAG
1. MCP
1. Agent
1. Fine-tuning
1. Quantization

Learn about the LLM, RAG, MCP, Agent, Fine-tuning & Quantization: [AI Engineering Explained: LLM, RAG, MCP, Agent, Fine-Tuning, Quantization](https://www.youtube.com/watch?v=lnfWvX66FUk)

### LLM Fundamentals

1. What are foundation models, and how have they changed AI engineering?
  1. Answer: Explained in this video: [AI Engineering Explained: LLM, RAG, MCP, Agent, Fine-Tuning, Quantization](https://www.youtube.com/watch?v=lnfWvX66FUk)
1. What is a Large Language Model (LLM), and how does it work?
  1. Answer: Explained in this video: [AI Engineering Explained: LLM, RAG, MCP, Agent, Fine-Tuning, Quantization](https://www.youtube.com/watch?v=lnfWvX66FUk)
1. Inside ChatGPT: What Happens After You Hit Enter?
  1. Answer: [Inside ChatGPT: What Happens After You Hit Enter](https://outcomeschool.substack.com/p/inside-chatgpt-what-happens-after)
1. What is the Transformer architecture and how does it work?
  1. Answer: [Decoding Transformer Architecture](https://outcomeschool.com/blog/decoding-transformer-architecture)
1. What are the key components of the Transformer architecture?
  1. Answer: [Decoding Transformer Architecture](https://outcomeschool.com/blog/decoding-transformer-architecture)
1. What is tokenization in LLMs?
  1. Answer: [Tokenization in Large Language Models (LLMs)](https://www.youtube.com/watch?v=sK2s9I84EVI)
1. Explain BPE (Byte Pair Encoding).
  1. Answer: [Byte Pair Encoding](https://outcomeschool.com/blog/bpe-in-llms)
1. Explain WordPiece and SentencePiece.
1. What is positional encoding, and why is it needed in Transformers?
  1. Answer: [Positional Embeddings in LLMs](https://outcomeschool.substack.com/p/positional-embeddings-in-llms)
1. What are embeddings?
  1. Answer: [Embeddings in Machine Learning](https://www.youtube.com/watch?v=LedXW6xl21s)
1. Explain the Query(Q), Key(K), and Value(V) in attention.
  1. Answer: [Math behind Attention 1. Q, K, and V](https://outcomeschool.com/blog/math-behind-attention-qkv)
1. What is self-attention, and how does it work in Transformers?
  1. Answer: [Self Attention in Transformers](https://outcomeschool.com/blog/self-attention-in-transformers)
1. What is Cross Attention in Transformers?
  1. Answer: [Cross Attention in Transformers](https://outcomeschool.com/blog/cross-attention-in-transformers)
1. Why do we scale the dot product attention by √dₖ in the Transformer architecture?
  1. Answer: [Math behind √dₖ Scaling Factor in Attention](https://outcomeschool.com/blog/scaling-dot-product-attention)
1. What is causal masking?
  1. Answer: [Causal Masking in Attention](https://outcomeschool.com/blog/causal-masking-in-attention)
1. What are multi-head attention mechanisms? Why use multiple attention heads?
  1. Answer: [Multi-Head Attention in Transformers](https://outcomeschool.com/blog/multi-head-attention-in-transformers)
1. What are Feed-Forward Networks in LLMs?
  1. Answer: [Feed-Forward Networks in LLMs](https://outcomeschool.com/blog/feed-forward-networks-in-llms)
1. What is the context window in LLMs, and why does it matter?
  1. Answer: [Context Window in LLMs](https://www.linkedin.com/posts/amit-shekhar-iitbhu_the-context-window-is-the-llms-working-memory-activity-7437754426175672320-MH9c)
1. Why is the context window limited in LLMs?
  1. Answer: [Why is the context window limited in LLMs?](https://www.youtube.com/watch?v=CGIhxIaOg3M&lc)
1. What is temperature in the context of LLMs, and how does it affect output?
  1. Answer: [What is temperature in the context of LLMs?](https://x.com/amitiitbhu/status/1964990603927687493)
1. Why is the first token slower than the rest in an LLM?
  1. Answer: [The First-Token Latency Problem in LLMs](https://www.youtube.com/watch?v=XD8DD4cEHu0)
1. Explain Top-p (nucleus) sampling and Top-k sampling. How do they differ?
1. What are logits, and how are they used in text generation?
  1. Answer: [Understanding Logits in Machine Learning](https://x.com/amitiitbhu/status/1927927814923207146)
1. What are skip connections (residual connections) in Transformers?
  1. Answer: [Skip connections (residual connections) in Transformers](https://www.linkedin.com/posts/amit-shekhar-iitbhu_machinelearning-llm-deeplearning-share-7414239846707392512-pQdQ)
1. What is the difference between open-source and closed-source LLMs? When would you choose one over the other?
1. What is the difference between encoder-only, decoder-only, and encoder-decoder Transformer architectures?
  1. Answer: [Encoder vs Decoder in Transformers](https://outcomeschool.com/blog/encoder-vs-decoder-in-transformers)
1. What is KV cache, and how does it speed up inference?
  1. Answer: [What is KV Cache in LLMs?](https://outcomeschool.com/blog/kv-cache-in-llms)
1. What is model distillation, and how is it used with LLMs?
  1. Answer: [How does Knowledge Distillation work?](https://outcomeschool.com/blog/how-does-knowledge-distillation-work)
1. What is Mixture of Experts (MoE), and how does it work in models like Mixtral?
  1. Answer: [Mixture of Experts Explained](https://outcomeschool.com/blog/mixture-of-experts)
1. What is the difference between dense and sparse models?
  1. Answer: [Mixture of Experts Explained](https://outcomeschool.com/blog/mixture-of-experts)
1. What is Flash Attention?
  1. Answer: [Decoding Flash Attention in LLMs](https://outcomeschool.com/blog/decoding-flash-attention)
1. What is Cross-Entropy Loss?
  1. Answer: [Math Behind Cross-Entropy Loss](https://outcomeschool.com/blog/math-behind-cross-entropy-loss)
1. What is Grouped-Query Attention (GQA), and how does it differ from Multi-Head Attention (MHA)?
  1. Answer: [Grouped Query Attention](https://outcomeschool.com/blog/grouped-query-attention)
1. How does Rotary Position Embedding (RoPE) work, and why is it preferred over learned positional embeddings?
  1. Answer: [Math Behind RoPE (Rotary Position Embedding)](https://outcomeschool.com/blog/math-behind-rope-rotary-position-embedding)
1. Explain Layer Normalization
  1. Answer: [Batch Normalization vs Layer Normalization](https://outcomeschool.com/blog/batch-normalization-vs-layer-normalization)
1. Explain RMSNorm (Root Mean Square Layer Normalization)
  1. Answer: [RMSNorm (Root Mean Square Layer Normalization)](https://outcomeschool.com/blog/rmsnorm-root-mean-square-layer-normalization)
1. Your LLM keeps ignoring your instructions. How do you make it follow structured output formats?
1. Your LLM-powered tool hits the context window limit on long documents. How do you handle it?
1. Your LLM does not admit when it does not know the answer. How do you make it say "I don't know"?
1. Your LLM generates responses that are too verbose. How do you control response length?
1. Your LLM memorized proprietary training data and leaks it in responses. How do you prevent this?
1. Your LLM coding assistant generates outdated code using deprecated libraries. How do you fix it?
1. Your tokenizer splits important domain terms into meaningless subword pieces. How do you fix it?
1. Your Transformer's KV cache grows too large during long sequence generation. How do you manage memory?
  1. Answer: [Paged Attention in LLMs](https://outcomeschool.com/blog/paged-attention-in-llms)
1. Your Transformer runs out of memory on long documents due to quadratic self-attention. How do you scale it?
1. Your distilled student model fails on the complex reasoning that the teacher model handled. How do you close the gap?
1. After RLHF alignment, your LLM became safer but lost capability on hard tasks. How do you manage the alignment tax?
1. Your RLHF-trained LLM is gaming the reward model instead of being genuinely helpful. How do you fix reward hacking?
  1. Answer: [Reinforcement Learning from Human Feedback (RLHF)](https://outcomeschool.com/blog/reinforcement-learning-from-human-feedback-rlhf)
1. Your chatbot loses context after 10 turns in a conversation. How do you maintain a long conversation context?
  1. Answer: [AI Agent Memory](https://outcomeschool.com/blog/ai-agent-memory)
1. Your chatbot fails when users switch topics mid-conversation. How do you handle topic switches?
1. Your QA system always generates an answer even when no answer exists in the context. How do you detect unanswerable questions?
1. Your summarization system hallucinated facts not in the original article. How do you fix it?
1. Your text generation repeats phrases in long outputs. How do you fix repetition?
1. Transformers work on text, so can they also understand images?
  1. Answer: [Decoding Vision Transformer (ViT)](https://outcomeschool.com/blog/decoding-vision-transformer-vit)
1. Small Language Models (SLMs)
  1. Answer: [Small Language Models (SLMs)](https://outcomeschool.com/blog/small-language-models-slms)
1. Large Reasoning Models (LRMs)
  1. Answer: [Large Reasoning Models (LRMs)](https://outcomeschool.com/blog/large-reasoning-models)
1. What are Autoregressive Models?
  1. Answer: [Autoregressive Models](https://outcomeschool.com/blog/autoregressive-models)
1. Explain the difference between autoregressive and masked language modeling.
1. Proximal Policy Optimization (PPO)
  1. Answer: [Proximal Policy Optimization (PPO)](https://outcomeschool.com/blog/proximal-policy-optimization-ppo)
1. Direct Preference Optimization (DPO)
  1. Answer: [Direct Preference Optimization (DPO)](https://outcomeschool.com/blog/direct-preference-optimization-dpo)
1. Group Relative Policy Optimization (GRPO)
  1. Answer: [Group Relative Policy Optimization (GRPO)](https://outcomeschool.com/blog/group-relative-policy-optimization-grpo)
1. Recursive Language Models (RLMs)
  1. Answer: [Recursive Language Models (RLMs)](https://outcomeschool.com/blog/recursive-language-models)
1. Continual Learning in LLMs
  1. Answer: [Continual Learning in LLMs](https://outcomeschool.com/blog/continual-learning-in-llms)
1. How do Diffusion Language Models (DLMs) work?
  1. Answer: [How do Diffusion Language Models (DLMs) work?](https://outcomeschool.com/blog/how-do-diffusion-language-models-dlms-work)
1. How Does LLM Watermarking Work?
  1. Answer: [How Does LLM Watermarking Work?](https://outcomeschool.com/blog/how-does-llm-watermarking-work)

### Prompt Engineering

1. What is prompt engineering, and why is it critical for AI applications?
1. Explain zero-shot, one-shot, and few-shot prompting with examples.
  1. Answer: [Explain zero-shot, one-shot, and few-shot prompting with examples](https://www.linkedin.com/posts/pallavi-shekhar_llm-prompting-ai-activity-7441801012472078336-JsHr)
1. What is chain-of-thought (CoT) prompting, and when should you use it?
  1. Answer: [How does Chain-of-Thought (CoT) Prompting work?](https://outcomeschool.com/blog/how-does-chain-of-thought-prompting-work)
1. Explain self-consistency prompting and how it improves reasoning.
1. What is tree-of-thought prompting?
1. What is ReAct (Reasoning + Acting) prompting, and how does it work?
  1. Answer: [ReAct Agent](https://outcomeschool.com/blog/react-agent)
1. What is a system prompt, and how does it influence model behavior?
1. How do you structure prompts for consistent structured output (JSON, XML)?
1. What is prompt injection, and how do you defend against it?
  1. Answer: [Prompt Injection in LLMs](https://outcomeschool.com/blog/prompt-injection-in-llms)
1. What is jailbreaking in LLMs, and what are common jailbreak techniques?
1. How do you optimize prompts for cost and latency?
1. What is the difference between prompt engineering and prompt tuning?
1. What is a prompt template, and how do you design one for production use?
1. How do you handle multi-turn conversations with LLMs?
1. What is role prompting, and when is it effective?
1. What is prompt chaining, and how do you design a chain of prompts for complex tasks?
  1. Answer: [How does Prompt Chaining work?](https://outcomeschool.com/blog/how-does-prompt-chaining-work)
1. How do you evaluate and iterate on prompt quality?
1. What are meta-prompts, and how can they be used to generate prompts?
1. What are the common failure modes in prompting, and how do you debug them?
1. How do you handle edge cases and adversarial inputs in prompt design?
1. What is the "lost in the middle" problem in long-context prompting?
  1. Answer: [The Lost in the Middle Problem in LLMs](https://outcomeschool.com/blog/lost-in-the-middle-problem-in-llms)
1. What are output parsers, and why are they needed for production applications?
1. How do you handle multi-language prompting effectively?
1. Your few-shot prompting gives inconsistent results across similar inputs. How do you stabilize it?
1. Your LLM classification system is too sensitive to prompt wording changes. How do you reduce prompt sensitivity?
1. Your chatbot's system prompt containing proprietary business logic is being leaked by users. How do you prevent it?
1. Your LLM agent is vulnerable to prompt injection that reveals the system prompt. How do you defend it?
  1. Answer: [Prompt Injection in LLMs](https://outcomeschool.com/blog/prompt-injection-in-llms)
1. Your chain-of-thought prompting is not improving LLM accuracy on reasoning tasks. What do you fix?
1. Your AI system works in English but fails for other languages. How do you add multilingual support?
1. Your zero-shot cross-lingual transfer from English fails on other languages. How do you fix it?

### Retrieval-Augmented Generation (RAG)

1. What is Retrieval-Augmented Generation (RAG), and why is it important?
  1. Answer: Explained in this video: [AI Engineering Explained: LLM, RAG, MCP, Agent, Fine-Tuning, Quantization](https://www.youtube.com/watch?v=lnfWvX66FUk)
1. Explain the architecture of a basic RAG system.
  1. Answer: Explained in this video: [AI Engineering Explained: LLM, RAG, MCP, Agent, Fine-Tuning, Quantization](https://www.youtube.com/watch?v=lnfWvX66FUk)
1. What are the key components of a RAG pipeline?
  1. Answer: Explained in this video: [AI Engineering Explained: LLM, RAG, MCP, Agent, Fine-Tuning, Quantization](https://www.youtube.com/watch?v=lnfWvX66FUk)
1. What are chunking strategies, and how do you choose the right chunk size?
1. Compare fixed-size chunking, semantic chunking, and recursive chunking.
1. What are embedding models, and how do they convert text to vectors?
  1. Answer: [What are Embeddings?](https://outcomeschool.com/blog/what-are-embeddings)
1. How do you choose an embedding model for your RAG system?
1. Explain Agentic RAG.
  1. Answer: [Agentic RAG](https://outcomeschool.com/blog/agentic-rag)
1. What is hybrid search, and why is it better than pure vector search?
  1. Answer: [How does Hybrid Search work?](https://outcomeschool.com/blog/how-does-hybrid-search-work)
1. What is re-ranking, and how does it improve RAG retrieval quality?
  1. Answer: [How does a Reranker work?](https://outcomeschool.com/blog/how-does-a-reranker-work)
1. How do you handle multi-document and multi-hop questions in RAG?
1. What is the "lost in the middle" problem in RAG systems?
  1. Answer: [The Lost in the Middle Problem in LLMs](https://outcomeschool.com/blog/lost-in-the-middle-problem-in-llms)
1. How do you evaluate a RAG system? Explain faithfulness, relevance, and context precision/recall.
1. Explain Self-RAG. How does the model decide when to retrieve?
1. What is GraphRAG, and when would you use it over traditional RAG?
  1. Answer: [GraphRAG](https://outcomeschool.com/blog/graphrag)
1. How do you handle structured data (tables, SQL databases) in a RAG pipeline?
1. What are the common failure modes of RAG systems, and how do you debug them?
1. How do you handle document updates and maintain freshness in a RAG system?
1. How do you optimize RAG for latency in production?
1. What is the role of metadata filtering in RAG systems?
1. Compare RAG vs fine-tuning. When would you use each?
  1. Answer: Explained in this video: [AI Engineering Explained: LLM, RAG, MCP, Agent, Fine-Tuning, Quantization](https://www.youtube.com/watch?v=lnfWvX66FUk)
1. What is query transformation in RAG (HyDE, query decomposition, step-back prompting)?
  1. Answer: [How does HyDE work in RAG?](https://outcomeschool.com/blog/how-does-hyde-work)
1. How do you implement citation and source attribution in RAG?
1. How do you scale a RAG system to millions of documents?
1. What is parent-child chunking, and how does it improve retrieval?
1. Your RAG system is hallucinating despite having the right context. How do you fix it?
1. Your RAG chunk overlap causes redundant results. How do you reduce redundancy?
1. Your RAG retrieval is too slow with a large knowledge base. How do you speed it up?
1. Your RAG system returns duplicate results. How do you deduplicate?
1. Your RAG system needs per-user access control on internal documents. How do you implement it?
1. Your RAG system fails on domain-specific jargon. How do you fix it?
1. Your text-only RAG system now needs to handle images and tables. How do you extend it?
1. Your RAG knowledge base gets updated frequently and needs versioning. How do you manage it?
1. Your RAG system fails on multi-hop questions that require combining multiple facts. How do you fix it?
1. Your enterprise RAG system returns contradictory answers from different source documents. How do you resolve conflicts?
1. Your RAG system returns outdated answers from an evolving knowledge base. How do you keep it current?
1. Your RAG system struggles with PDF documents containing tables and layouts. How do you fix PDF parsing?

### AI Agents and Agentic Systems

1. What is an AI agent, and how does it differ from a simple LLM call?
  1. Answer: Explained in this video: [AI Engineering Explained: LLM, RAG, MCP, Agent, Fine-Tuning, Quantization](https://www.youtube.com/watch?v=lnfWvX66FUk) and [AI Agent Explained](https://outcomeschool.com/blog/ai-agent)
1. AI Agent Memory
  1. Answer: [AI Agent Memory](https://outcomeschool.com/blog/ai-agent-memory)
1. Harness Engineering in AI
  1. Answer: [Harness Engineering in AI](https://outcomeschool.com/blog/harness-engineering-in-ai)
1. Explain the ReAct (Reasoning + Acting) agent architecture.
  1. Answer: [ReAct Agent](https://outcomeschool.com/blog/react-agent)
1. What is the Plan-and-Execute agent pattern?
  1. Answer: [Plan-and-Execute Agent](https://outcomeschool.com/blog/plan-and-execute-agent)
1. What is tool use (function calling) in LLMs, and how does it enable agents?
  1. Answer: Explained in this video: [AI Engineering Explained: LLM, RAG, MCP, Agent, Fine-Tuning, Quantization](https://www.youtube.com/watch?v=lnfWvX66FUk)
1. How do you design and define tools for an AI agent?
  1. Answer: Explained in this video: [AI Engineering Explained: LLM, RAG, MCP, Agent, Fine-Tuning, Quantization](https://www.youtube.com/watch?v=lnfWvX66FUk)
1. What is the difference between single-agent and multi-agent systems?
  1. Answer: [Multi-Agent Systems](https://outcomeschool.com/blog/multi-agent-systems)
1. What is Model Context Protocol (MCP), and how does it standardize tool integration?
  1. Answer: Explained in this video: [AI Engineering Explained: LLM, RAG, MCP, Agent, Fine-Tuning, Quantization](https://www.youtube.com/watch?v=lnfWvX66FUk)
1. What are AI SubAgents?
  1. Answer: [AI SubAgents](https://outcomeschool.com/blog/ai-subagents)
1. What are the different types of agent memory (short-term, long-term, episodic)?
  1. Answer: [AI Agent Memory](https://outcomeschool.com/blog/ai-agent-memory)
1. How do you handle agent failures and implement error recovery?
1. What is an agent loop, and how does it decide when to stop?
  1. Answer: [AI Agent Loop](https://outcomeschool.com/blog/ai-agent-loop)
1. Context Engineering
  1. Answer: [Context Engineering](https://outcomeschool.com/blog/context-engineering)
1. How does context compaction work?
  1. Answer: [How does context compaction work?](https://outcomeschool.com/blog/how-does-context-compaction-work)
1. Loop Engineering
  1. Answer: [Loop Engineering](https://outcomeschool.com/blog/what-is-loop-engineering)
1. Graph Engineering
  1. Answer: [Graph Engineering](https://outcomeschool.com/blog/what-is-graph-engineering) 
1. How AI Agents Communicate?
  1. Answer: [How AI Agents Communicate](https://outcomeschool.com/blog/how-ai-agents-communicate)
1. What are Agent Skills?
  1. Answer: [What are Agent Skills?](https://outcomeschool.com/blog/what-are-agent-skills)
1. How do you evaluate and test AI agents?
  1. Answer: [AI Agent Evaluation](https://outcomeschool.com/blog/ai-agent-evaluation)
1. What are the security risks of agentic systems, and how do you mitigate them?
1. What is the difference between reactive and proactive agents?
1. How do you manage token consumption and cost in long-running agent workflows?
1. What is the human-in-the-loop pattern for agents, and when is it needed?
1. How do you implement guardrails for AI agents to prevent harmful actions?
  1. Answer: [How do LLM guardrails work?](https://outcomeschool.com/blog/how-do-llm-guardrails-work)
1. What is agent reflection, and how does it improve agent performance?
  1. Answer: [Reflection Agent](https://outcomeschool.com/blog/reflection-agent)
1. What is the difference between code-generating agents and tool-calling agents?
1. How do you handle multi-modal inputs and outputs in agentic systems?
1. How do you implement state management in complex agent workflows?
  1. Answer: [How does LangGraph work?](https://outcomeschool.com/blog/how-does-langgraph-work)
1. How do you build a customer support agent with escalation logic?
1. What is agent orchestration, and how do you implement it?
  1. Answer: [AI Orchestration](https://outcomeschool.com/blog/ai-orchestration)
1. How do you build a code execution agent safely using sandboxed environments?
1. Your AI agent is stuck in an infinite loop. How do you detect and break the cycle?
  1. Answer: [Fix an infinite loop in an AI agent](https://www.linkedin.com/posts/pallavi-shekhar_ai-aiagents-machinelearning-share-7440257380707364864-5Ycc)
1. Your AI agent gets conflicting answers from different tools. How does it reconcile them?
1. Your AI agent burns too many tokens per task. How do you reduce token consumption?
  1. Answer: [How would you reduce the token consumption?](https://www.linkedin.com/posts/pallavi-shekhar_ai-aiagents-machinelearning-activity-7439550125015994368-LTmE)
1. Your AI agent keeps exceeding its budget per task. How do you enforce budget limits?
1. Your AI agent hallucinates tool capabilities and passes wrong inputs. How do you fix it?
1. Your AI agent deleted a production database. How do you prevent irreversible actions?
1. Your AI agent has many tools, but keeps picking the wrong one. How do you improve tool selection?
1. Your AI agent takes too long to complete a task. How do you speed it up?
1. Your LLM selects the right tool but extracts the wrong parameters. How do you fix parameter extraction?
1. How do Computer-Use Agents work?
  1. Answer: [How do Computer-Use Agents work?](https://outcomeschool.com/blog/how-do-computer-use-agents-work)
1. How does LangChain work?
  1. Answer: [How does LangChain work?](https://outcomeschool.com/blog/how-does-langchain-work)
1. How does LangGraph work?
  1. Answer: [How does LangGraph work?](https://outcomeschool.com/blog/how-does-langgraph-work)
1. What is OKF (Open Knowledge Format)?
  1. Answer: [What is OKF (Open Knowledge Format)?](https://outcomeschool.com/blog/what-is-okf-open-knowledge-format) 

### Fine-Tuning and Model Adaptation

1. What is fine-tuning, and when should you fine-tune an LLM?
  1. Answer: Explained in this video: [AI Engineering Explained: LLM, RAG, MCP, Agent, Fine-Tuning, Quantization](https://www.youtube.com/watch?v=lnfWvX66FUk)
1. Explain the difference between full fine-tuning and parameter-efficient fine-tuning (PEFT).
  1. Answer: Explained in this video: [AI Engineering Explained: LLM, RAG, MCP, Agent, Fine-Tuning, Quantization](https://www.youtube.com/watch?v=lnfWvX66FUk)
1. What is LoRA (Low-Rank Adaptation), and how does it work?
  1. Answer: Explained in this video: [AI Engineering Explained: LLM, RAG, MCP, Agent, Fine-Tuning, Quantization](https://www.youtube.com/watch?v=lnfWvX66FUk)
1. What is QLoRA, and how does it enable fine-tuning on consumer hardware?
  1. Answer: Explained in this video: [AI Engineering Explained: LLM, RAG, MCP, Agent, Fine-Tuning, Quantization](https://www.youtube.com/watch?v=lnfWvX66FUk)
1. How does fine-tuning work?
  1. Answer: [How does fine-tuning work?](https://outcomeschool.com/blog/how-does-fine-tuning-work)
1. Explain Prefix Tuning and Prompt Tuning. How are they different from LoRA?
1. What is adapter-based fine-tuning?
  1. Answer: Explained in this video: [AI Engineering Explained: LLM, RAG, MCP, Agent, Fine-Tuning, Quantization](https://www.youtube.com/watch?v=lnfWvX66FUk)
1. What is RLHF (Reinforcement Learning from Human Feedback), and how is it used to align LLMs?
  1. Answer: [Reinforcement Learning from Human Feedback (RLHF)](https://outcomeschool.com/blog/reinforcement-learning-from-human-feedback-rlhf)
1. What is instruction tuning, and why is it important for chat models?
  1. Answer: [Decoding InstructGPT](https://outcomeschool.com/blog/decoding-instructgpt)
1. How do you prepare a dataset for fine-tuning an LLM?
1. What is catastrophic forgetting, and how do you prevent it during fine-tuning?
  1. Answer: [Continual Learning in LLMs](https://outcomeschool.com/blog/continual-learning-in-llms)
1. When should you choose fine-tuning over RAG over prompt engineering?
1. How do you evaluate a fine-tuned model's performance?
  1. Answer: [LLM Evaluation](https://outcomeschool.com/blog/llm-evaluation)
1. What is synthetic data generation, and how do you use it for fine-tuning?
1. What are the key hyperparameters for fine-tuning (learning rate, epochs, batch size, LoRA rank)?
  1. Answer: [LoRA 1. Low-Rank Adaptation of LLMs](https://outcomeschool.com/blog/lora-low-rank-adaptation-of-llms)
1. How do you fine-tune a model for a specific domain (legal, medical, finance)?
1. What is continual pre-training, and when would you use it?
1. How do you merge multiple LoRA adapters?
  1. Answer: [LoRA 1. Low-Rank Adaptation of LLMs](https://outcomeschool.com/blog/lora-low-rank-adaptation-of-llms)
1. What is the difference between SFT (Supervised Fine-Tuning) and alignment training?
1. What is RLAIF (RL from AI Feedback), and how does it differ from RLHF?
1. What is knowledge distillation for fine-tuning, and what are the legal considerations?
  1. Answer: [How does Knowledge Distillation work?](https://outcomeschool.com/blog/how-does-knowledge-distillation-work)
1. Your fine-tuned LLM produces factually wrong outputs due to training data quality issues. How do you fix it?
1. You must choose between LoRA and full fine-tuning for a domain-specific assistant. How do you decide?
  1. Answer: [LoRA 1. Low-Rank Adaptation of LLMs](https://outcomeschool.com/blog/lora-low-rank-adaptation-of-llms)
1. Your fine-tuned model memorized training data verbatim instead of learning patterns. How do you fix overfitting?
1. Your fine-tuned LLM forgot its general capabilities after domain-specific fine-tuning. How do you fix catastrophic forgetting?
  1. Answer: [Continual Learning in LLMs](https://outcomeschool.com/blog/continual-learning-in-llms)
1. Your RLHF preference data has low annotator agreement. How do you ensure data quality?

### Vector Databases and Embeddings

1. What are embeddings in the context of AI engineering?
  1. Answer: [Embeddings in Machine Learning](https://www.youtube.com/watch?v=LedXW6xl21s)
1. How do embedding models convert text to vectors?
  1. Answer: [What are Embeddings?](https://outcomeschool.com/blog/what-are-embeddings)
1. What is the difference between sparse and dense embeddings?
1. Explain cosine similarity, dot product, and Euclidean distance for vector search.
  1. Answer: [How does a Vector Database work?](https://outcomeschool.com/blog/how-does-a-vector-database-work)
1. What is a vector database, and how does it differ from a traditional database?
  1. Answer: [How does a Vector Database work?](https://outcomeschool.com/blog/how-does-a-vector-database-work)
1. How does Approximate Nearest Neighbor (ANN) search work?
  1. Answer: [How does Approximate Nearest Neighbor (ANN) search work?](https://outcomeschool.com/blog/how-does-approximate-nearest-neighbor-ann-search-work)
1. How do you choose the right embedding model for your use case?
1. What is embedding dimensionality, and how does it affect performance and cost?
1. How do you handle embedding drift when the embedding model is updated?
1. What are multi-modal embeddings, and how are they generated?
  1. Answer: [Multimodal AI](https://outcomeschool.com/blog/multimodal-ai)
1. How do you index and query multi-tenant data in a vector database?
1. What is quantization of embeddings, and how does it reduce storage costs?
1. How do you benchmark and evaluate embedding model quality?
1. What is the role of metadata in vector databases?
  1. Answer: [How does a Vector Database work?](https://outcomeschool.com/blog/how-does-a-vector-database-work)
1. How do you handle large-scale vector search with billions of vectors?
  1. Answer: [How does Approximate Nearest Neighbor (ANN) search work?](https://outcomeschool.com/blog/how-does-approximate-nearest-neighbor-ann-search-work)
1. What is hybrid search (combining keyword search with vector search)?
  1. Answer: [How does Hybrid Search work?](https://outcomeschool.com/blog/how-does-hybrid-search-work) 
1. How do you fine-tune an embedding model for a specific domain?
1. Your vector database for RAG is consuming too much memory. How do you reduce it?
1. Your vector database cannot scale to millions of embeddings. How do you fix the bottleneck?
1. Your new embedding model has different dimensions from the existing vectors in production. How do you handle the mismatch?
1. Your vector search returns irrelevant results despite high similarity scores. How do you fix it?
1. You deployed a new embedding model, and search quality crashed overnight. How do you handle embedding drift?
1. Your semantic search fails for short queries. How do you improve it?

### AI System Design

1. Design ChatGPT: Training to Serving (End to End)
1. Design a RAG System (Chat with Your Documents)
1. Design Memory for a Personal AI Assistant
  1. Answer: [AI Agent Memory](https://outcomeschool.com/blog/ai-agent-memory)
1. Design a Deep Research Agent
1. Design a Multi-Agent Customer Support System
  1. Answer: [Multi-Agent Systems](https://outcomeschool.com/blog/multi-agent-systems)
1. Design an On-Device AI Assistant
1. Design a Multimodal Search System (Text, Image, Video)
1. Design an LLM Inference Platform (vLLM-as-a-Service)
  1. Answer: [How does vLLM work?](https://outcomeschool.com/blog/how-does-vllm-work) and [LLM Inference Optimization](https://outcomeschool.com/blog/llm-inference-optimization)
1. Design an LLM Evaluation Platform
  1. Answer: [LLM Evaluation](https://outcomeschool.com/blog/llm-evaluation)
1. Design a Text-to-Image Generation Service (Midjourney-like)
1. Design a Music Generation Service (Suno-like)
1. Design a Video Generation Service (Sora-like)
1. Design an AI Coding Agent.
  1. Answer: [How does Claude Code work?](https://outcomeschool.com/blog/how-does-claude-code-work) and [How does Cursor work?](https://outcomeschool.com/blog/how-does-cursor-work)
1. Design a code generation and review system.
1. Design a content moderation system using AI.
1. Design a real-time AI recommendation system.
1. Design an AI-powered email assistant.
1. Design a medical diagnosis assistant using AI.
1. Design a fraud detection system powered by LLMs.
1. Design an AI-powered data extraction pipeline from unstructured documents.
1. Design a personalized learning assistant.
1. Design an AI system for automated code migration.
1. Design an AI-powered legal document review system.
1. Design a conversational AI system with memory across sessions.
  1. Answer: [AI Agent Memory](https://outcomeschool.com/blog/ai-agent-memory)
1. How do you design for latency vs quality trade-offs in AI systems?
1. How do you implement caching strategies for LLM applications?
1. How do you design rate limiting and cost management for AI APIs?
1. How do you handle failover and fallback strategies for AI systems?
1. How do you design an AI system for high availability and fault tolerance?
1. How do you design an AI system that gracefully degrades when the model is unavailable?
1. What are the key considerations for multi-region deployment of AI systems?
1. Design an AI-powered search engine for an e-commerce platform.
1. Design an AI gateway/proxy for managing LLM access across an organization.
1. How do you design a RAG system that handles conflicting information across sources?
1. How do you approach capacity planning for an AI system?
1. Design a multi-tenant AI chatbot platform where each business gets a custom chatbot.
1. Design an AI meeting summarizer system for thousands of meetings daily.
1. Design an AI notification system that prioritizes instead of broadcasting.
1. Design an AI-powered anomaly detection system for cloud infrastructure.
1. Design an AI-powered document processing pipeline for financial institutions.
1. Design an AI dynamic pricing engine.
1. Design an AI resume screening system that handles 100K applications per week.
1. Design an AI voice assistant architecture.
1. Design a multi-agent workflow system where agents collaborate on complex tasks.
  1. Answer: [Multi-Agent Systems](https://outcomeschool.com/blog/multi-agent-systems)
1. Design a real-time AI transcription system for concurrent audio streams.
1. Design an AI-powered live streaming content moderation system.

### LLMOps and Production AI

1. How does Prompt Caching work?
  1. Answer: [How does Prompt Caching work?](https://outcomeschool.com/blog/how-does-prompt-caching-work)
1. Prefill vs Decode
  1. Answer: [Prefill vs Decode: LLM Inference Optimization](https://outcomeschool.com/blog/prefill-vs-decode-llm-inference-optimization)
1. Explain the AI product lifecycle from ideation to production.
1. What is LLMOps, and how does it differ from traditional MLOps?
1. How do you serve LLMs in production?
1. What is model quantization?
  1. Answer: Explained in this video: [AI Engineering Explained: LLM, RAG, MCP, Agent, Fine-Tuning, Quantization](https://www.youtube.com/watch?v=lnfWvX66FUk)
1. How do you monitor LLM applications in production?
  1. Answer: [AI Agent Observability](https://outcomeschool.com/blog/ai-agent-observability)
1. What is LLM observability?
  1. Answer: [AI Agent Observability](https://outcomeschool.com/blog/ai-agent-observability)
1. What are guardrails for LLMs, and how do you implement them?
  1. Answer: [How do LLM guardrails work?](https://outcomeschool.com/blog/how-do-llm-guardrails-work)
1. How do you implement content filtering for AI outputs?
1. How do you estimate the cost of running an AI-powered feature in production?
1. How do you optimize LLM inference costs in production?
  1. Answer: [LLM Inference Optimization](https://outcomeschool.com/blog/llm-inference-optimization)
1. How do you implement A/B testing for LLM systems?
1. What is CI/CD for AI applications, and how does it differ from traditional CI/CD?
1. How do you version and manage prompts in production?
1. What is model versioning, and how do you handle model rollbacks?
1. How do you implement rate limiting and throttling for LLM APIs?
1. How do you handle model updates and migrations without downtime?
1. What is the role of feature flags in AI deployments?
1. How do you implement logging and tracing for LLM applications?
  1. Answer: [AI Agent Observability](https://outcomeschool.com/blog/ai-agent-observability)
1. How do you handle PII and sensitive data in LLM inputs and outputs?
1. What is a gateway pattern for LLM API management?
1. How does Token Streaming work?
  1. Answer: [How does Token Streaming work?](https://outcomeschool.com/blog/how-does-token-streaming-work)
1. How do you implement streaming responses for real-time AI applications?
  1. Answer: [How does Token Streaming work?](https://outcomeschool.com/blog/how-does-token-streaming-work)
1. How does vLLM work?
  1. Answer: [How does vLLM work?](https://outcomeschool.com/blog/how-does-vllm-work)
1. How does SGLang work?
  1. Answer: [How does SGLang work?](https://outcomeschool.com/blog/how-does-sglang-work)
1. What are the key SLAs and metrics for production AI systems (latency, throughput, availability)?
1. Cloud vs on-device Model Deployment for AI applications.
  1. Answer: [Cloud vs On-Device Model Deployment](https://outcomeschool.com/blog/cloud-vs-on-device-model-deployment)
1. How do you implement fallback strategies when the primary model is unavailable or rate-limited?
1. How do you implement structured output from LLMs reliably in production?
1. How do you handle long contexts efficiently in production (context compression, prefix caching)?
1. What is semantic routing, and how do you implement it in a multi-model system?
  1. Answer: [LLM Routing](https://outcomeschool.com/blog/llm-routing)
1. How do you manage secrets and API keys securely in LLM applications?
1. Your LLM API has latency spikes during peak hours. How do you stabilize it?
1. Your LLM costs are too high in production. How do you reduce costs without degrading quality?
1. Your application is hitting LLM provider rate limits during peak hours. How do you handle it?
1. Your application depends on one LLM provider. How do you switch providers without downtime?
1. Your AI system handles 100 requests/sec but crashes at 5000. How do you scale for concurrent requests?
1. A traffic spike brings down your AI system. How do you handle peak traffic?
1. One LLM provider outage took down your entire system. How do you eliminate single points of failure?
1. Your multi-LLM pipeline fails when one model in the chain breaks. How do you handle orchestration failure?
  1. Answer: [AI Orchestration](https://outcomeschool.com/blog/ai-orchestration)
1. Your AI pipeline has zero visibility into which step is failing. How do you add observability?
  1. Answer: [AI Agent Observability](https://outcomeschool.com/blog/ai-agent-observability)
1. You quantized your LLM, but accuracy dropped significantly. How do you minimize quantization loss?
1. One failing AI component can take down your entire platform. How do you design graceful degradation?

### Evaluation and Testing

1. AI Agent Evaluation
  1. Answer: [AI Agent Evaluation](https://outcomeschool.com/blog/ai-agent-evaluation)
1. LLM Evaluation
  1. Answer: [LLM Evaluation](https://outcomeschool.com/blog/llm-evaluation)
1. AI Agent Observability
  1. Answer: [AI Agent Observability](https://outcomeschool.com/blog/ai-agent-observability)
1. What is evaluation-driven development for AI applications?
1. How do you evaluate LLM outputs? What metrics do you use?
  1. Answer: [LLM Evaluation](https://outcomeschool.com/blog/llm-evaluation)
1. Explain BLEU, ROUGE, and BERTScore. When would you use each?
  1. Answer: [LLM Evaluation](https://outcomeschool.com/blog/llm-evaluation)
1. What is G-Eval, and how does it use LLMs for evaluation?
  1. Answer: [LLM as a Judge](https://outcomeschool.com/blog/llm-as-a-judge)
1. What is LLM-as-a-judge evaluation, and what are its limitations?
  1. Answer: [LLM as a Judge](https://outcomeschool.com/blog/llm-as-a-judge)
1. How do you conduct human evaluation for AI systems?
1. What is red teaming, and how do you red team an LLM application?
1. How do you detect and measure hallucinations in LLM outputs?
1. What is adversarial testing for AI systems?
1. How do you build a regression test suite for AI applications?
1. What are benchmark suites (MMLU, HumanEval, GSM8K), and how do you interpret them?
  1. Answer: [LLM Evaluation](https://outcomeschool.com/blog/llm-evaluation)
1. How do you evaluate a RAG system end-to-end?
1. How do you evaluate the quality of AI agents?
  1. Answer: [AI Agent Evaluation](https://outcomeschool.com/blog/ai-agent-evaluation)
1. What is the difference between offline and online evaluation for AI systems?
1. How do you measure factual consistency in LLM outputs?
1. How do you evaluate multi-turn conversation quality?
1. What is the role of golden datasets in AI evaluation?
1. How do you implement continuous evaluation for production AI systems?
1. How do you evaluate bias in AI model outputs?
1. How do you compare two models or prompts in a statistically rigorous way?
1. How do you evaluate the robustness of an LLM application across input variations?
1. What are the key differences between evaluating traditional ML vs LLM applications?
1. How do you set up an evaluation framework from scratch for a new LLM application?
  1. Answer: [LLM Evaluation](https://outcomeschool.com/blog/llm-evaluation)
1. Your model passes one fairness metric but fails another. How do you handle conflicting audit results?
1. Your model was fair at deployment, but became biased 6 months later. How do you monitor continuously?
1. An external auditor cannot reproduce your model's results. How do you ensure audit reproducibility?
1. How do you structure red teaming for an LLM chatbot before launch?
1. How do you red team a multimodal model where text-only safety tests miss cross-modal attacks?

### AI Safety, Ethics, and Responsible AI

1. What are hallucinations in LLMs, and how do you mitigate them?
1. What is prompt injection, and what are the different types (direct, indirect)?
  1. Answer: [Prompt Injection in LLMs](https://outcomeschool.com/blog/prompt-injection-in-llms)
1. How do you implement input and output guardrails for AI systems?
  1. Answer: [How do LLM guardrails work?](https://outcomeschool.com/blog/how-do-llm-guardrails-work)
1. What is AI alignment, and why is it important?
1. How do you detect and mitigate bias in AI systems?
1. What are the key data privacy considerations (GDPR, CCPA) when building AI applications?
1. How do you handle PII in LLM inputs and outputs?
1. What is explainability in AI, and why does it matter?
1. What is the difference between interpretability and explainability?
1. How do you build trust with users in AI-powered applications?
1. What are adversarial attacks on AI systems, and how do you defend against them?
1. What is data poisoning, and how can it affect AI models?
1. How do you implement content safety filters for AI-generated content?
1. What is responsible AI, and what frameworks exist for implementing it?
1. How do you handle copyright and intellectual property concerns with AI-generated content?
1. What is the EU AI Act, and how does it affect AI engineering?
1. How do you implement audit trails and logging for AI decisions?
1. What is model card documentation, and why is it important?
1. How do you handle misuse and abuse of AI systems in production?
1. What is differential privacy, and how can it be applied during model training?
1. How would you design an AI incident response plan?
1. What is the NIST AI Risk Management Framework (AI RMF)?
1. Your healthcare chatbot gives medical diagnoses it should not make. How do you add safety guardrails?
  1. Answer: [How do LLM guardrails work?](https://outcomeschool.com/blog/how-do-llm-guardrails-work)
1. Your AI system is reproducing copyrighted material verbatim. How do you prevent this?
1. Your resume screening AI rejects more female candidates for engineering roles. How do you fix gender bias?
1. Your AI model passes bias checks by gender and race separately, but fails for intersectional groups. How do you handle it?
1. Your AI denied a loan, and the customer demands a GDPR explanation. How do you provide one?
1. A user invokes the right to be forgotten, but their data is in your model weights. How do you comply?
1. The EU AI Act may classify your AI system as high-risk. How do you comply?
1. Your differentially private model lost significant accuracy. How do you balance privacy and utility?
1. One malicious participant is poisoning your federated learning model. How do you defend against it?
1. Your AI hiring model uses proxy features for protected attributes. How do you eliminate proxy discrimination?
1. Your predictive model creates a feedback loop of biased outcomes. How do you break it?
1. Your AI generates fake news images. How do you implement watermarking for AI-generated content?
1. Your AI denies a service, and the user has no way to challenge it. How do you design an appeals process?
1. An auditor asks why your AI rejected a request 6 months ago, and you have no logs. How do you build audit trails?
1. You removed PII, but users were re-identified from anonymized data. How do you prevent re-identification?
1. A pre-trained model from an open-source repo may contain a hidden backdoor. How do you detect it?
1. Your LLM's training data was deliberately poisoned by an adversary. How do you respond?
1. Your AI mental health chatbot gave harmful advice to a user in crisis. How do you mitigate harm?
1. Your AI system caused incorrect critical decisions. How do you run a blameless post-mortem?
1. Radiologists agree with AI 98% of the time, even when it is wrong. How do you prevent human over-reliance on AI?
1. Your content moderation flags normal cultural expressions as offensive in other markets. How do you adapt cross-culturally?
1. Your AI training produces massive carbon emissions. How do you reduce environmental impact?

### Multimodal AI

1. What are Multimodal AI models, and how do they process different types of data?
  1. Answer: [Multimodal AI](https://outcomeschool.com/blog/multimodal-ai)
1. How do vision-language models process images?
  1. Answer: [Multimodal AI](https://outcomeschool.com/blog/multimodal-ai)
1. How does CLIP work, and why is it important for multi-modal AI?
1. What are the key architectures for multi-modal models?
1. How does image generation work with diffusion models (Stable Diffusion, DALL-E, Flux)?
  1. Answer: [Diffusion Models](https://outcomeschool.com/blog/diffusion-models)
1. What is text-to-speech (TTS), and what models are used for it?
1. How does speech-to-text (Whisper) work?
1. What is multi-modal RAG, and how does it differ from text-only RAG?
1. How do you build a system that processes both images and text?
1. What are multi-modal embeddings, and how are they used for cross-modal search?
  1. Answer: [Multimodal AI](https://outcomeschool.com/blog/multimodal-ai)
1. How do you evaluate multi-modal AI systems?
1. What are the challenges of real-time multi-modal AI processing?
1. How do you handle video understanding with AI?
1. What is visual question answering (VQA)?
1. What is document understanding, and how do models parse documents with layouts?
1. How do you fine-tune a vision-language model?
1. What are the latency and cost considerations for multi-modal AI in production?
1. How do you handle multi-modal content moderation?
1. What is text-to-video generation, and what are the current state-of-the-art approaches?
1. Explain Multimodal Fusion Techniques: Early Fusion vs Late Fusion.
1. Your vision-language model generates factually incorrect image descriptions. How do you fix it?
1. Your VLM answers single-image questions but fails on multi-page documents. How do you fix it?
1. Your multimodal LLM ignores the image and generates descriptions from text alone. How do you fix it?
1. Your diffusion model ignores precise control requirements in text prompts. How do you improve controllability?
1. Your diffusion model generates sharp but repetitive images. How do you balance quality vs diversity?
1. Your diffusion model takes too long per image. How do you speed up sampling?

### AI Infrastructure and Scalability

1. How do you improve inference speed in production LLM deployments?
  1. Answer: [LLM Inference Optimization](https://www.youtube.com/watch?v=jV2sCj4lHYk)
1. LLM optimization techniques
  1. Answer: [LLM optimization techniques](https://www.linkedin.com/posts/pallavi-shekhar_5-llm-optimization-techniques-lets-understand-activity-7442067281532325888-4aOS)
1. How do you select GPUs for LLM inference?
1. What is model parallelism vs data parallelism in distributed training?
1. What is tensor parallelism, and how does it help serve large models?
1. What is pipeline parallelism?
1. How does continuous batching improve LLM inference throughput?
  1. Answer: [Continuous Batching in LLMs](https://outcomeschool.com/blog/continuous-batching-in-llms)
1. What is speculative decoding, and how does it speed up inference?
  1. Answer: [Speculative Decoding](https://outcomeschool.com/blog/speculative-decoding)
1. What is KV cache, and how do you manage memory for it?
  1. Answer: [What is KV Cache in LLMs?](https://outcomeschool.com/blog/kv-cache-in-llms)
1. What is Paged Attention?
  1. Answer: [Paged Attention in LLMs](https://outcomeschool.com/blog/paged-attention-in-llms)
1. How does GGUF work?
  1. Answer: [How does GGUF work?](https://outcomeschool.com/blog/how-does-gguf-work)
1. How do you optimize inference for edge and mobile deployment?
1. What is model quantization (INT8, INT4, FP16, BF16), and how does it affect quality?
  1. Answer: Explained in this video: [AI Engineering Explained: LLM, RAG, MCP, Agent, Fine-Tuning, Quantization](https://www.youtube.com/watch?v=lnfWvX66FUk)
1. How do you implement auto-scaling for AI workloads?
1. What is the role of load balancing in AI serving infrastructure?
1. How do you manage GPU memory for serving multiple models?
1. What is model sharding, and when would you use it?
1. How do you implement request queuing and priority scheduling for AI services?
1. What are the cost trade-offs between self-hosted and API-based AI inference?
1. How do you handle cold start latency for serverless AI deployments?
1. How do you implement model caching to reduce redundant computations?
1. What is the difference between synchronous and asynchronous inference, and when do you use each?
1. What is FSDP (Fully Sharded Data Parallel), and how does it differ from DeepSpeed ZeRO?
1. How do you monitor and profile LLM inference in production (TTFT, inter-token latency, GPU utilization)?
1. What is model routing at the infrastructure level, and how do you route requests based on complexity and cost?
  1. Answer: [LLM Routing](https://outcomeschool.com/blog/llm-routing)

### Coding and Practical Implementation

1. Implement a basic RAG pipeline using an embedding model and a vector database.
1. Build a simple AI agent with tool use (e.g., calculator, web search).
  1. Answer: [ReAct Agent](https://outcomeschool.com/blog/react-agent)
1. Implement semantic search using embeddings and cosine similarity.
  1. Answer: [How does Semantic Search work?](https://outcomeschool.com/blog/how-does-semantic-search-work) and [How does a Vector Database work?](https://outcomeschool.com/blog/how-does-a-vector-database-work)
1. Write code for different text chunking strategies (fixed-size, recursive, semantic).
1. Implement a prompt template system with variable substitution.
1. Build an evaluation pipeline for LLM outputs using LLM-as-a-judge.
  1. Answer: [LLM as a Judge](https://outcomeschool.com/blog/llm-as-a-judge)
1. Implement streaming responses for an LLM API.
  1. Answer: [How does Token Streaming work?](https://outcomeschool.com/blog/how-does-token-streaming-work)
1. Build a simple vector similarity search from scratch.
1. Implement a conversation memory system for a chatbot (sliding window, summary, buffer).
1. Write code to detect and handle hallucinations in LLM outputs.
1. Implement a retry mechanism with exponential backoff for LLM API calls.
1. Write a function calling (tool use) handler for an LLM API.
  1. Answer: [How does Function Calling work in LLMs?](https://outcomeschool.com/blog/how-does-function-calling-work-in-llms)
1. Implement a simple re-ranker for search results.
  1. Answer: [How does a Reranker work?](https://outcomeschool.com/blog/how-does-a-reranker-work)
1. Build a basic document parser that extracts text from PDFs and splits it into chunks.
1. Implement cosine similarity, dot product, and Euclidean distance functions from scratch.
1. Write code to implement token counting and context window management.
1. Build a simple prompt versioning system.
1. Implement a caching layer for LLM responses.
1. Implement semantic caching for LLM queries (cache responses for semantically similar queries).
  1. Answer: [How does Semantic Caching work?](https://outcomeschool.com/blog/how-does-semantic-caching-work)
1. Write code to detect prompt injection attempts in user inputs.
1. Implement an LLM output guardrails system that checks for off-topic responses and PII leakage.
  1. Answer: [How do LLM guardrails work?](https://outcomeschool.com/blog/how-do-llm-guardrails-work)
1. Build a multi-agent system where agents have different roles and collaborate on a task.
  1. Answer: [Multi-Agent Systems](https://outcomeschool.com/blog/multi-agent-systems)

### Behavioral and Scenario-Based Questions

1. What is AI Engineering, and how does it differ from Machine Learning Engineering?
1. How do you decide whether a problem needs AI or a traditional software solution?
1. How do you measure the ROI of an AI feature?
1. How do you handle hallucinations when they occur in a production AI system?
1. How do you decide between using an LLM API vs self-hosting an open-source model?
1. How do you manage stakeholder expectations for AI projects?
1. Describe your approach to debugging a poor-performing RAG system.
1. How do you stay current with the rapidly evolving AI landscape?
1. How do you balance innovation with reliability in AI systems?
1. Tell me about a challenging AI project you worked on. What was the problem? What approach did you take? What trade-offs did you make? What was the outcome?
1. How would you handle a situation where an AI model produces biased or harmful outputs in production?
1. How do you approach cost optimization for an AI system that's exceeding budget?
1. Describe a time when you had to choose between model accuracy and latency. How did you make the decision?
1. How would you handle a situation where your AI system's quality degrades over time?
1. How do you communicate AI limitations to non-technical stakeholders?
1. How would you approach building an AI feature with limited labeled data?
1. Describe your experience working with cross-functional teams on AI projects.
1. Where do you see AI engineering heading in the next 3-5 years?
1. Why are you interested in this AI engineering role?
1. Your PM wants to ship an AI feature with a 15% hallucination rate on edge cases. How do you communicate the risk?
1. A non-technical executive asks why your AI feature cannot be 100% accurate. How do you explain LLM limitations?
1. You need to choose between a complex agentic system that scores 15% better on benchmarks, or a simpler RAG pipeline that is easier to maintain. How do you decide?

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
