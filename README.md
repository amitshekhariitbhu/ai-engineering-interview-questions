<p align="center">
    <img alt="AI Engineering Interview Questions and Answers" src="https://github.com/amitshekhariitbhu/ai-engineering-interview-questions/blob/main/assets/banner.png">
</p>

# AI Engineering Interview Questions and Answers

> AI Engineering Interview Questions and Answers - Your Cheat Sheet For AI Engineering Interviews
>
> These interview questions and answers are helpful for roles such as:
>
> - AI Engineer
> - Gen AI Engineer
> - LLM Engineer
> - Agentic AI Engineer
> - AI Agent Engineer
> - Forward Deployed Engineer
> - AI Solutions Architect
> - AI Platform Engineer
> - Applied AI Engineer
> - MLOps Engineer
> - LLMOps Engineer

## Table of Contents

- [Must Know](#must-know)
- [LLM Fundamentals](#llm-fundamentals)
- [Prompt Engineering](#prompt-engineering)
- [Retrieval-Augmented Generation (RAG)](#retrieval-augmented-generation-rag)
- [AI Agents and Agentic Systems](#ai-agents-and-agentic-systems)
- [Fine-Tuning and Model Adaptation](#fine-tuning-and-model-adaptation)
- [Vector Databases and Embeddings](#vector-databases-and-embeddings)
- [AI System Design](#ai-system-design)
- [LLMOps and Production AI](#llmops-and-production-ai)
- [Evaluation and Testing](#evaluation-and-testing)
- [AI Safety, Ethics, and Responsible AI](#ai-safety-ethics-and-responsible-ai)
- [Multimodal AI](#multimodal-ai)
- [AI Infrastructure and Scalability](#ai-infrastructure-and-scalability)
- [Coding and Practical Implementation](#coding-and-practical-implementation)
- [Behavioral and Scenario-Based Questions](#behavioral-and-scenario-based-questions)

### Prepared and maintained by the **Founder** of [Outcome School](https://outcomeschool.com): Amit Shekhar

### Follow Amit Shekhar

- [X/Twitter](https://twitter.com/amitiitbhu)
- [LinkedIn](https://www.linkedin.com/in/amit-shekhar-iitbhu)
- [GitHub](https://github.com/amitshekhariitbhu)

### Follow Outcome School

- [YouTube](https://youtube.com/@OutcomeSchool)
- [X/Twitter](https://x.com/outcome_school)
- [LinkedIn](https://www.linkedin.com/company/outcomeschool)
- [GitHub](https://github.com/OutcomeSchool)

## I teach at Outcome School

- [AI and Machine Learning](https://outcomeschool.com/program/ai-and-machine-learning)

---

> **Note: We will keep updating this with new questions and answers.**

---

### Must Know

- LLM
- RAG
- MCP
- Agent
- Fine-tuning
- Quantization

Learn about the LLM, RAG, MCP, Agent, Fine-tuning & Quantization: [AI Engineering Explained: LLM, RAG, MCP, Agent, Fine-Tuning, Quantization](https://www.youtube.com/watch?v=lnfWvX66FUk)

### LLM Fundamentals

- What are foundation models, and how have they changed AI engineering?
  - Answer: Explained in this video: [AI Engineering Explained: LLM, RAG, MCP, Agent, Fine-Tuning, Quantization](https://www.youtube.com/watch?v=lnfWvX66FUk)
- What is a Large Language Model (LLM), and how does it work?
  - Answer: Explained in this video: [AI Engineering Explained: LLM, RAG, MCP, Agent, Fine-Tuning, Quantization](https://www.youtube.com/watch?v=lnfWvX66FUk)
- Inside ChatGPT: What Happens After You Hit Enter?
  - Answer: [Inside ChatGPT: What Happens After You Hit Enter](https://outcomeschool.substack.com/p/inside-chatgpt-what-happens-after)
- What is the Transformer architecture and how does it work?
  - Answer: [Decoding Transformer Architecture](https://outcomeschool.com/blog/decoding-transformer-architecture)
- What are the key components of the Transformer architecture?
  - Answer: [Decoding Transformer Architecture](https://outcomeschool.com/blog/decoding-transformer-architecture)
- Walk me through what happens, step by step, in one forward pass of a decoder-only Transformer.
  - Answer: [Decoding Transformer Architecture](https://outcomeschool.com/blog/decoding-transformer-architecture)
- What is tokenization in LLMs?
  - Answer: [Tokenization in LLMs](https://outcomeschool.com/blog/tokenization-in-llms) and [Tokenization in Large Language Models (LLMs)](https://www.youtube.com/watch?v=sK2s9I84EVI)
- Explain BPE (Byte Pair Encoding).
  - Answer: [Byte Pair Encoding](https://outcomeschool.com/blog/bpe-in-llms)
- Explain WordPiece and SentencePiece.
- What is positional encoding, and why is it needed in Transformers?
  - Answer: [Positional Embeddings in LLMs](https://outcomeschool.substack.com/p/positional-embeddings-in-llms)
- What are embeddings?
  - Answer: [Embeddings in Machine Learning](https://www.youtube.com/watch?v=LedXW6xl21s)
- Explain the Query(Q), Key(K), and Value(V) in attention.
  - Answer: [Math behind Attention - Q, K, and V](https://outcomeschool.com/blog/math-behind-attention-qkv)
- What is self-attention, and how does it work in Transformers?
  - Answer: [Self Attention in Transformers](https://outcomeschool.com/blog/self-attention-in-transformers)
- What is Cross Attention in Transformers?
  - Answer: [Cross Attention in Transformers](https://outcomeschool.com/blog/cross-attention-in-transformers)
- Why do we scale the dot product attention by √dₖ in the Transformer architecture?
  - Answer: [Math behind √dₖ Scaling Factor in Attention](https://outcomeschool.com/blog/scaling-dot-product-attention)
- What is causal masking?
  - Answer: [Causal Masking in Attention](https://outcomeschool.com/blog/causal-masking-in-attention)
- What are multi-head attention mechanisms? Why use multiple attention heads?
  - Answer: [Multi-Head Attention in Transformers](https://outcomeschool.com/blog/multi-head-attention-in-transformers)
- What are Feed-Forward Networks in LLMs?
  - Answer: [Feed-Forward Networks in LLMs](https://outcomeschool.com/blog/feed-forward-networks-in-llms)
- What is Generative AI?
  - Answer: [What is Generative AI?](https://outcomeschool.com/blog/what-is-generative-ai)
- What is the context window in LLMs, and why does it matter?
  - Answer: [Context Window in LLMs](https://www.linkedin.com/posts/amit-shekhar-iitbhu_the-context-window-is-the-llms-working-memory-activity-7437754426175672320-MH9c)
- Why is the context window limited in LLMs?
  - Answer: [Why is the context window limited in LLMs?](https://www.youtube.com/watch?v=CGIhxIaOg3M&lc)
- What is temperature in the context of LLMs, and how does it affect output?
  - Answer: [How does Temperature control LLM output?](https://outcomeschool.com/blog/how-does-temperature-control-llm-output)
- Why is the first token slower than the rest in an LLM?
  - Answer: [The First-Token Latency Problem in LLMs](https://www.youtube.com/watch?v=XD8DD4cEHu0)
- Explain Top-p (nucleus) sampling and Top-k sampling. How do they differ?
  - Answer: [How do Top-k and Top-p Sampling work?](https://outcomeschool.com/blog/how-do-top-k-and-top-p-sampling-work) 
- Compare greedy decoding, beam search, top-k, top-p, and temperature sampling. When does each fail?
  - Answer: [How do Top-k and Top-p Sampling work?](https://outcomeschool.com/blog/how-do-top-k-and-top-p-sampling-work) 
- What are logits, and how are they used in text generation?
  - Answer: [Understanding Logits in Machine Learning](https://x.com/amitiitbhu/status/1927927814923207146)
- What are stop tokens in LLMs, and how does an LLM know when to stop generating?
  - Answer: [Stop Tokens in LLMs](https://outcomeschool.com/blog/stop-tokens-in-llms)
- What is the difference between a stop token and a stop sequence?
  - Answer: [Stop Tokens in LLMs](https://outcomeschool.com/blog/stop-tokens-in-llms)
- What are skip connections (residual connections) in Transformers?
  - Answer: [Skip connections (residual connections) in Transformers](https://www.linkedin.com/posts/amit-shekhar-iitbhu_machinelearning-llm-deeplearning-share-7414239846707392512-pQdQ)
- What is the difference between open-source and closed-source LLMs? When would you choose one over the other?
- What is the difference between encoder-only, decoder-only, and encoder-decoder Transformer architectures?
  - Answer: [Encoder vs Decoder in Transformers](https://outcomeschool.com/blog/encoder-vs-decoder-in-transformers)
- What is KV cache, and how does it speed up inference?
  - Answer: [What is KV Cache in LLMs?](https://outcomeschool.com/blog/kv-cache-in-llms)
- Estimate the KV cache memory needed to serve a large model. How does it constrain batch size and context length?
  - Answer: [KV Cache Compression](https://outcomeschool.com/blog/kv-cache-compression)
- KV Cache Compression
  - Answer: [KV Cache Compression](https://outcomeschool.com/blog/kv-cache-compression)
- What is model distillation, and how is it used with LLMs?
  - Answer: [How does Knowledge Distillation work?](https://outcomeschool.com/blog/how-does-knowledge-distillation-work)
- What is Mixture of Experts (MoE), and how does it work in models like Mixtral?
  - Answer: [Mixture of Experts Explained](https://outcomeschool.com/blog/mixture-of-experts)
- What is the difference between dense and sparse models?
  - Answer: [Mixture of Experts Explained](https://outcomeschool.com/blog/mixture-of-experts)
- How does DeepSeek-V4 work?
  - Answer: [DeepSeek-V4 Architecture Explained](https://outcomeschool.com/blog/decoding-deepseek-v4)
- What is Flash Attention?
  - Answer: [Decoding Flash Attention in LLMs](https://outcomeschool.com/blog/decoding-flash-attention)
- What is Cross-Entropy Loss?
  - Answer: [Math Behind Cross-Entropy Loss](https://outcomeschool.com/blog/math-behind-cross-entropy-loss)
- What is Grouped-Query Attention (GQA), and how does it differ from Multi-Head Attention (MHA)?
  - Answer: [Grouped Query Attention](https://outcomeschool.com/blog/grouped-query-attention)
- How does Sliding Window Attention work?
  - Answer: [How does Sliding Window Attention work?](https://outcomeschool.com/blog/how-does-sliding-window-attention-work)
- How do Attention Sinks work?
  - Answer: [How do Attention Sinks work?](https://outcomeschool.com/blog/how-do-attention-sinks-work)
- How does Rotary Position Embedding (RoPE) work, and why is it preferred over learned positional embeddings?
  - Answer: [Math Behind RoPE (Rotary Position Embedding)](https://outcomeschool.com/blog/math-behind-rope-rotary-position-embedding)
- Explain Layer Normalization
  - Answer: [Batch Normalization vs Layer Normalization](https://outcomeschool.com/blog/batch-normalization-vs-layer-normalization)
- Explain RMSNorm (Root Mean Square Layer Normalization)
  - Answer: [RMSNorm (Root Mean Square Layer Normalization)](https://outcomeschool.com/blog/rmsnorm-root-mean-square-layer-normalization)
- Why do modern Transformers use Pre-LayerNorm (Pre-Norm) instead of Post-LayerNorm?
  - Answer: [RMSNorm (Root Mean Square Layer Normalization)](https://outcomeschool.com/blog/rmsnorm-root-mean-square-layer-normalization)
- What are scaling laws (Chinchilla), and how do they guide model size vs training data decisions?
- Your LLM keeps ignoring your instructions. How do you make it follow structured output formats?
- Your LLM-powered tool hits the context window limit on long documents. How do you handle it?
- Your LLM does not admit when it does not know the answer. How do you make it say "I don't know"?
- Your LLM generates responses that are too verbose. How do you control response length?
- Your LLM memorized proprietary training data and leaks it in responses. How do you prevent this?
- Your LLM coding assistant generates outdated code using deprecated libraries. How do you fix it?
- Your tokenizer splits important domain terms into meaningless subword pieces. How do you fix it?
- Your Transformer's KV cache grows too large during long sequence generation. How do you manage memory?
  - Answer: [Paged Attention in LLMs](https://outcomeschool.com/blog/paged-attention-in-llms)
- Your Transformer runs out of memory on long documents due to quadratic self-attention. How do you scale it?
  - Answer: [How does Sliding Window Attention work?](https://outcomeschool.com/blog/how-does-sliding-window-attention-work) and [Decoding Flash Attention in LLMs](https://outcomeschool.com/blog/decoding-flash-attention)
- Your distilled student model fails on the complex reasoning that the teacher model handled. How do you close the gap?
- After RLHF alignment, your LLM became safer but lost capability on hard tasks. How do you manage the alignment tax?
- Your RLHF-trained LLM is gaming the reward model instead of being genuinely helpful. How do you fix reward hacking?
  - Answer: [Reinforcement Learning from Human Feedback (RLHF)](https://outcomeschool.com/blog/reinforcement-learning-from-human-feedback-rlhf)
- Your chatbot loses context after 10 turns in a conversation. How do you maintain a long conversation context?
  - Answer: [AI Agent Memory](https://outcomeschool.com/blog/ai-agent-memory)
- Your chatbot fails when users switch topics mid-conversation. How do you handle topic switches?
- Your QA system always generates an answer even when no answer exists in the context. How do you detect unanswerable questions?
- Your summarization system hallucinated facts not in the original article. How do you fix it?
- Your text generation repeats phrases in long outputs. How do you fix repetition?
- Transformers work on text, so can they also understand images?
  - Answer: [Decoding Vision Transformer (ViT)](https://outcomeschool.com/blog/decoding-vision-transformer-vit)
- Small Language Models (SLMs)
  - Answer: [Small Language Models (SLMs)](https://outcomeschool.com/blog/small-language-models-slms)
- Large Reasoning Models (LRMs)
  - Answer: [Large Reasoning Models (LRMs)](https://outcomeschool.com/blog/large-reasoning-models)
- Jev and System One Models
  - Answer: [Jev and System One Models Explained](https://outcomeschool.com/blog/jev-and-system-one-models-explained)
- What are Autoregressive Models?
  - Answer: [Autoregressive Models](https://outcomeschool.com/blog/autoregressive-models)
- Explain the difference between autoregressive and masked language modeling.
- Proximal Policy Optimization (PPO)
  - Answer: [Proximal Policy Optimization (PPO)](https://outcomeschool.com/blog/proximal-policy-optimization-ppo)
- Direct Preference Optimization (DPO)
  - Answer: [Direct Preference Optimization (DPO)](https://outcomeschool.com/blog/direct-preference-optimization-dpo)
- Group Relative Policy Optimization (GRPO)
  - Answer: [Group Relative Policy Optimization (GRPO)](https://outcomeschool.com/blog/group-relative-policy-optimization-grpo)
- Recursive Language Models (RLMs)
  - Answer: [Recursive Language Models (RLMs)](https://outcomeschool.com/blog/recursive-language-models)
- Continual Learning in LLMs
  - Answer: [Continual Learning in LLMs](https://outcomeschool.com/blog/continual-learning-in-llms)
- What is Recursive Self-Improvement (RSI)?
  - Answer: [What is Recursive Self-Improvement (RSI)?](https://outcomeschool.com/blog/what-is-recursive-self-improvement-rsi)
- How do Diffusion Language Models (DLMs) work?
  - Answer: [How do Diffusion Language Models (DLMs) work?](https://outcomeschool.com/blog/how-do-diffusion-language-models-dlms-work)
- How Does LLM Watermarking Work?
  - Answer: [How Does LLM Watermarking Work?](https://outcomeschool.com/blog/how-does-llm-watermarking-work)
- How do RNNs and Transformers differ?
  - Answer: [How do RNNs and Transformers differ?](https://outcomeschool.com/blog/how-do-rnns-and-transformers-differ)

### Prompt Engineering

- What is prompt engineering, and why is it critical for AI applications?
- Explain zero-shot, one-shot, and few-shot prompting with examples.
  - Answer: [Explain zero-shot, one-shot, and few-shot prompting with examples](https://www.linkedin.com/posts/pallavi-shekhar_llm-prompting-ai-activity-7441801012472078336-JsHr)
- What is chain-of-thought (CoT) prompting, and when should you use it?
  - Answer: [How does Chain-of-Thought (CoT) Prompting work?](https://outcomeschool.com/blog/how-does-chain-of-thought-prompting-work)
- Explain self-consistency prompting and how it improves reasoning.
- What is tree-of-thought prompting?
- What is ReAct (Reasoning + Acting) prompting, and how does it work?
  - Answer: [ReAct Agent](https://outcomeschool.com/blog/react-agent)
- What is a system prompt, and how does it influence model behavior?
- How do you structure prompts for consistent structured output (JSON, XML)?
- What is prompt injection, and how do you defend against it?
  - Answer: [Prompt Injection in LLMs](https://outcomeschool.com/blog/prompt-injection-in-llms)
- What is jailbreaking in LLMs, and what are common jailbreak techniques?
  - Answer: [Prompt Injection in LLMs](https://outcomeschool.com/blog/prompt-injection-in-llms)
- How do you optimize prompts for cost and latency?
- What is the difference between prompt engineering and prompt tuning?
- What is a prompt template, and how do you design one for production use?
- How do you handle multi-turn conversations with LLMs?
- What is role prompting, and when is it effective?
- What is prompt chaining, and how do you design a chain of prompts for complex tasks?
  - Answer: [How does Prompt Chaining work?](https://outcomeschool.com/blog/how-does-prompt-chaining-work)
- How do you evaluate and iterate on prompt quality?
- What are meta-prompts, and how can they be used to generate prompts?
- What are the common failure modes in prompting, and how do you debug them?
- How do you handle edge cases and adversarial inputs in prompt design?
- What is the "lost in the middle" problem in long-context prompting?
  - Answer: [The Lost in the Middle Problem in LLMs](https://outcomeschool.com/blog/lost-in-the-middle-problem-in-llms)
- What are output parsers, and why are they needed for production applications?
- How do you handle multi-language prompting effectively?
- Your few-shot prompting gives inconsistent results across similar inputs. How do you stabilize it?
- Your LLM classification system is too sensitive to prompt wording changes. How do you reduce prompt sensitivity?
- Your chatbot's system prompt containing proprietary business logic is being leaked by users. How do you prevent it?
- Your LLM agent is vulnerable to prompt injection that reveals the system prompt. How do you defend it?
  - Answer: [Prompt Injection in LLMs](https://outcomeschool.com/blog/prompt-injection-in-llms)
- Your chain-of-thought prompting is not improving LLM accuracy on reasoning tasks. What do you fix?
- Your AI system works in English but fails for other languages. How do you add multilingual support?
- Your zero-shot cross-lingual transfer from English fails on other languages. How do you fix it?

### Retrieval-Augmented Generation (RAG)

- What is Retrieval-Augmented Generation (RAG), and why is it important?
  - Answer: Explained in this video: [AI Engineering Explained: LLM, RAG, MCP, Agent, Fine-Tuning, Quantization](https://www.youtube.com/watch?v=lnfWvX66FUk)
- Explain the architecture of a basic RAG system.
  - Answer: Explained in this video: [AI Engineering Explained: LLM, RAG, MCP, Agent, Fine-Tuning, Quantization](https://www.youtube.com/watch?v=lnfWvX66FUk)
- What are the key components of a RAG pipeline?
  - Answer: Explained in this video: [AI Engineering Explained: LLM, RAG, MCP, Agent, Fine-Tuning, Quantization](https://www.youtube.com/watch?v=lnfWvX66FUk)
- What are chunking strategies, and how do you choose the right chunk size?
  - Answer: [Chunking Strategies for RAG](https://outcomeschool.com/blog/chunking-strategies-for-rag)
- Compare fixed-size chunking, semantic chunking, and recursive chunking.
  - Answer: [Chunking Strategies for RAG](https://outcomeschool.com/blog/chunking-strategies-for-rag)
- What are embedding models, and how do they convert text to vectors?
  - Answer: [What are Embeddings?](https://outcomeschool.com/blog/what-are-embeddings)
- How do you choose an embedding model for your RAG system?
- Explain Agentic RAG.
  - Answer: [Agentic RAG](https://outcomeschool.com/blog/agentic-rag)
- What is hybrid search, and why is it better than pure vector search?
  - Answer: [How does Hybrid Search work?](https://outcomeschool.com/blog/how-does-hybrid-search-work)
- What is re-ranking, and how does it improve RAG retrieval quality?
  - Answer: [How does a Reranker work?](https://outcomeschool.com/blog/how-does-a-reranker-work)
- What is ColBERT, and how does late interaction retrieval work?
  - Answer: [ColBERT - Late Interaction Retrieval Explained](https://outcomeschool.com/blog/decoding-colbert)
- Compare reranker architectures: cross-encoder, ColBERT, and LLM-based rerankers.
  - Answer: [How does a Reranker work?](https://outcomeschool.com/blog/how-does-a-reranker-work) and [ColBERT - Late Interaction Retrieval Explained](https://outcomeschool.com/blog/decoding-colbert)
- How do you handle multi-document and multi-hop questions in RAG?
  - Answer: [Agentic RAG](https://outcomeschool.com/blog/agentic-rag) and [GraphRAG](https://outcomeschool.com/blog/graphrag)
- What is the "lost in the middle" problem in RAG systems?
  - Answer: [The Lost in the Middle Problem in LLMs](https://outcomeschool.com/blog/lost-in-the-middle-problem-in-llms)
- How do you evaluate a RAG system? Explain faithfulness, relevance, and context precision/recall.
  - Answer: [LLM Evaluation](https://outcomeschool.com/blog/llm-evaluation)
- Explain Self-RAG. How does the model decide when to retrieve?
  - Answer: [Agentic RAG](https://outcomeschool.com/blog/agentic-rag)
- What is GraphRAG, and when would you use it over traditional RAG?
  - Answer: [GraphRAG](https://outcomeschool.com/blog/graphrag)
- Vectorless RAG
  - Answer: [Vectorless RAG](https://outcomeschool.com/blog/vectorless-rag)
- How do you handle structured data (tables, SQL databases) in a RAG pipeline?
- What are the common failure modes of RAG systems, and how do you debug them?
- How do you handle document updates and maintain freshness in a RAG system?
- How do you optimize RAG for latency in production?
- What is the role of metadata filtering in RAG systems?
  - Answer: [How does a Vector Database work?](https://outcomeschool.com/blog/how-does-a-vector-database-work)
- Compare RAG vs fine-tuning. When would you use each?
  - Answer: Explained in this video: [AI Engineering Explained: LLM, RAG, MCP, Agent, Fine-Tuning, Quantization](https://www.youtube.com/watch?v=lnfWvX66FUk)
- Long context windows keep getting cheaper. When should you use retrieval (RAG) vs putting everything in the context window?
  - Answer: [The Lost in the Middle Problem in LLMs](https://outcomeschool.com/blog/lost-in-the-middle-problem-in-llms)
- What is query transformation in RAG (HyDE, query decomposition, step-back prompting)?
  - Answer: [How does HyDE work in RAG?](https://outcomeschool.com/blog/how-does-hyde-work)
- How do you implement citation and source attribution in RAG?
- How do you scale a RAG system to millions of documents?
  - Answer: [How does Approximate Nearest Neighbor (ANN) search work?](https://outcomeschool.com/blog/how-does-approximate-nearest-neighbor-ann-search-work)
- What is parent-child chunking, and how does it improve retrieval?
  - Answer: [Chunking Strategies for RAG](https://outcomeschool.com/blog/chunking-strategies-for-rag)
- Your RAG system is hallucinating despite having the right context. How do you fix it?
- Your RAG chunk overlap causes redundant results. How do you reduce redundancy?
- Your RAG retrieval is too slow with a large knowledge base. How do you speed it up?
  - Answer: [How does Approximate Nearest Neighbor (ANN) search work?](https://outcomeschool.com/blog/how-does-approximate-nearest-neighbor-ann-search-work)
- Your RAG system returns duplicate results. How do you deduplicate?
- Your RAG system needs per-user access control on internal documents. How do you implement it?
- Your RAG system fails on domain-specific jargon. How do you fix it?
  - Answer: [How does Hybrid Search work?](https://outcomeschool.com/blog/how-does-hybrid-search-work)
- Your text-only RAG system now needs to handle images and tables. How do you extend it?
- Your RAG knowledge base gets updated frequently and needs versioning. How do you manage it?
- Your RAG system fails on multi-hop questions that require combining multiple facts. How do you fix it?
  - Answer: [Agentic RAG](https://outcomeschool.com/blog/agentic-rag) and [GraphRAG](https://outcomeschool.com/blog/graphrag)
- Your enterprise RAG system returns contradictory answers from different source documents. How do you resolve conflicts?
- Your RAG system returns outdated answers from an evolving knowledge base. How do you keep it current?
- Your RAG system struggles with PDF documents containing tables and layouts. How do you fix PDF parsing?

### AI Agents and Agentic Systems

- What is an AI agent, and how does it differ from a simple LLM call?
  - Answer: Explained in this video: [AI Engineering Explained: LLM, RAG, MCP, Agent, Fine-Tuning, Quantization](https://www.youtube.com/watch?v=lnfWvX66FUk) and [AI Agent Explained](https://outcomeschool.com/blog/ai-agent)
- AI Agent Memory
  - Answer: [AI Agent Memory](https://outcomeschool.com/blog/ai-agent-memory)
- Harness Engineering in AI
  - Answer: [Harness Engineering in AI](https://outcomeschool.com/blog/harness-engineering-in-ai)
- What matters more for an agentic coding tool like Claude Code: the model or the harness?
  - Answer: [Harness Engineering in AI](https://outcomeschool.com/blog/harness-engineering-in-ai) and [How does Claude Code work?](https://outcomeschool.com/blog/how-does-claude-code-work)
- Explain the ReAct (Reasoning + Acting) agent architecture.
  - Answer: [ReAct Agent](https://outcomeschool.com/blog/react-agent)
- What is the Plan-and-Execute agent pattern?
  - Answer: [Plan-and-Execute Agent](https://outcomeschool.com/blog/plan-and-execute-agent)
- What is tool use (function calling) in LLMs, and how does it enable agents?
  - Answer: Explained in this video: [AI Engineering Explained: LLM, RAG, MCP, Agent, Fine-Tuning, Quantization](https://www.youtube.com/watch?v=lnfWvX66FUk) and [How does Function Calling work in LLMs?](https://outcomeschool.com/blog/how-does-function-calling-work-in-llms)
- What is the difference between structured output and function calling?
  - Answer: [How does Function Calling work in LLMs?](https://outcomeschool.com/blog/how-does-function-calling-work-in-llms)
- How do you design and define tools for an AI agent?
  - Answer: Explained in this video: [AI Engineering Explained: LLM, RAG, MCP, Agent, Fine-Tuning, Quantization](https://www.youtube.com/watch?v=lnfWvX66FUk)
- How does an agent decide when to call a tool versus answering from its own knowledge?
- What is the difference between single-agent and multi-agent systems?
  - Answer: [Multi-Agent Systems](https://outcomeschool.com/blog/multi-agent-systems)
- When do multi-agent systems break down, and when is a single agent the better choice?
  - Answer: [Multi-Agent Systems](https://outcomeschool.com/blog/multi-agent-systems)
- What is Model Context Protocol (MCP), and how does it standardize tool integration?
  - Answer: Explained in this video: [AI Engineering Explained: LLM, RAG, MCP, Agent, Fine-Tuning, Quantization](https://www.youtube.com/watch?v=lnfWvX66FUk) and [What is MCP (Model Context Protocol)?](https://outcomeschool.com/blog/what-is-mcp-model-context-protocol)
- How does MCP differ from traditional function calling?
  - Answer: [What is MCP (Model Context Protocol)?](https://outcomeschool.com/blog/what-is-mcp-model-context-protocol) and [How does Function Calling work in LLMs?](https://outcomeschool.com/blog/how-does-function-calling-work-in-llms)
- What are AI SubAgents?
  - Answer: [AI SubAgents](https://outcomeschool.com/blog/ai-subagents)
- What are the different types of agent memory (short-term, long-term, episodic)?
  - Answer: [AI Agent Memory](https://outcomeschool.com/blog/ai-agent-memory)
- How do you handle agent failures and implement error recovery?
- What is an agent loop, and how does it decide when to stop?
  - Answer: [AI Agent Loop](https://outcomeschool.com/blog/ai-agent-loop)
- Context Engineering
  - Answer: [Context Engineering](https://outcomeschool.com/blog/context-engineering)
- How does context compaction work?
  - Answer: [How does context compaction work?](https://outcomeschool.com/blog/how-does-context-compaction-work)
- Loop Engineering
  - Answer: [Loop Engineering](https://outcomeschool.com/blog/what-is-loop-engineering)
- Graph Engineering
  - Answer: [Graph Engineering](https://outcomeschool.com/blog/what-is-graph-engineering)
- How AI Agents Communicate?
  - Answer: [How AI Agents Communicate](https://outcomeschool.com/blog/how-ai-agents-communicate)
- What are Agent Skills?
  - Answer: [What are Agent Skills?](https://outcomeschool.com/blog/what-are-agent-skills)
- How do you evaluate and test AI agents?
  - Answer: [AI Agent Evaluation](https://outcomeschool.com/blog/ai-agent-evaluation)
- What are the security risks of agentic systems, and how do you mitigate them?
  - Answer: [Prompt Injection in LLMs](https://outcomeschool.com/blog/prompt-injection-in-llms)
- Your agent reads untrusted content (emails, web pages, documents) and can call tools. How do you prevent indirect prompt injection and data exfiltration?
  - Answer: [Prompt Injection in LLMs](https://outcomeschool.com/blog/prompt-injection-in-llms)
- What is the difference between reactive and proactive agents?
- How do you manage token consumption and cost in long-running agent workflows?
  - Answer: [How does context compaction work?](https://outcomeschool.com/blog/how-does-context-compaction-work) and [How would you reduce the token consumption?](https://www.linkedin.com/posts/pallavi-shekhar_ai-aiagents-machinelearning-activity-7439550125015994368-LTmE)
- What is the human-in-the-loop pattern for agents, and when is it needed?
- How do you implement guardrails for AI agents to prevent harmful actions?
  - Answer: [How do LLM guardrails work?](https://outcomeschool.com/blog/how-do-llm-guardrails-work)
- What is agent reflection, and how does it improve agent performance?
  - Answer: [Reflection Agent](https://outcomeschool.com/blog/reflection-agent)
- What is the difference between code-generating agents and tool-calling agents?
- How do you handle multi-modal inputs and outputs in agentic systems?
- How do you implement state management in complex agent workflows?
  - Answer: [How does LangGraph work?](https://outcomeschool.com/blog/how-does-langgraph-work)
- How do you build a customer support agent with escalation logic?
- What is agent orchestration, and how do you implement it?
  - Answer: [AI Orchestration](https://outcomeschool.com/blog/ai-orchestration)
- What is Sakana Fugu, and how does it orchestrate a team of AI models?
  - Answer: [Sakana Fugu - The Technical Report Explained](https://outcomeschool.com/blog/decoding-sakana-fugu)
- How do you build a code execution agent safely using sandboxed environments?
- Your AI agent is stuck in an infinite loop. How do you detect and break the cycle?
  - Answer: [Fix an infinite loop in an AI agent](https://www.linkedin.com/posts/pallavi-shekhar_ai-aiagents-machinelearning-share-7440257380707364864-5Ycc)
- Your AI agent gets conflicting answers from different tools. How does it reconcile them?
- Your AI agent burns too many tokens per task. How do you reduce token consumption?
  - Answer: [How would you reduce the token consumption?](https://www.linkedin.com/posts/pallavi-shekhar_ai-aiagents-machinelearning-activity-7439550125015994368-LTmE)
- Your AI agent keeps exceeding its budget per task. How do you enforce budget limits?
  - Answer: [AI Agent Loop](https://outcomeschool.com/blog/ai-agent-loop)
- Your AI agent hallucinates tool capabilities and passes wrong inputs. How do you fix it?
- Your AI agent deleted a production database. How do you prevent irreversible actions?
- Your AI agent has many tools, but keeps picking the wrong one. How do you improve tool selection?
- Your AI agent takes too long to complete a task. How do you speed it up?
- Your long-running agent drifts after hours and confidently works on the wrong thing. How do you diagnose and fix it?
- Your LLM selects the right tool but extracts the wrong parameters. How do you fix parameter extraction?
- How do Computer-Use Agents work?
  - Answer: [How do Computer-Use Agents work?](https://outcomeschool.com/blog/how-do-computer-use-agents-work)
- How does LangChain work?
  - Answer: [How does LangChain work?](https://outcomeschool.com/blog/how-does-langchain-work)
- How does LangGraph work?
  - Answer: [How does LangGraph work?](https://outcomeschool.com/blog/how-does-langgraph-work)
- What is OKF (Open Knowledge Format)?
  - Answer: [What is OKF (Open Knowledge Format)?](https://outcomeschool.com/blog/what-is-okf-open-knowledge-format)

### Fine-Tuning and Model Adaptation

- What is fine-tuning, and when should you fine-tune an LLM?
  - Answer: Explained in this video: [AI Engineering Explained: LLM, RAG, MCP, Agent, Fine-Tuning, Quantization](https://www.youtube.com/watch?v=lnfWvX66FUk)
- Explain the difference between full fine-tuning and parameter-efficient fine-tuning (PEFT).
  - Answer: Explained in this video: [AI Engineering Explained: LLM, RAG, MCP, Agent, Fine-Tuning, Quantization](https://www.youtube.com/watch?v=lnfWvX66FUk)
- What is LoRA (Low-Rank Adaptation), and how does it work?
  - Answer: Explained in this video: [AI Engineering Explained: LLM, RAG, MCP, Agent, Fine-Tuning, Quantization](https://www.youtube.com/watch?v=lnfWvX66FUk)
- What is QLoRA, and how does it enable fine-tuning on consumer hardware?
  - Answer: Explained in this video: [AI Engineering Explained: LLM, RAG, MCP, Agent, Fine-Tuning, Quantization](https://www.youtube.com/watch?v=lnfWvX66FUk)
- How does fine-tuning work?
  - Answer: [How does fine-tuning work?](https://outcomeschool.com/blog/how-does-fine-tuning-work)
- Explain Prefix Tuning and Prompt Tuning. How are they different from LoRA?
  - Answer: [How does Prefix Tuning work?](https://outcomeschool.com/blog/how-does-prefix-tuning-work)
- What is adapter-based fine-tuning?
  - Answer: Explained in this video: [AI Engineering Explained: LLM, RAG, MCP, Agent, Fine-Tuning, Quantization](https://www.youtube.com/watch?v=lnfWvX66FUk)
- Explain the difference between pre-training, supervised fine-tuning (SFT), and preference optimization (RLHF/DPO).
  - Answer: [Decoding InstructGPT](https://outcomeschool.com/blog/decoding-instructgpt)
- What is RLHF (Reinforcement Learning from Human Feedback), and how is it used to align LLMs?
  - Answer: [Reinforcement Learning from Human Feedback (RLHF)](https://outcomeschool.com/blog/reinforcement-learning-from-human-feedback-rlhf)
- What is Deep RL from Human Preferences, the paper that started RLHF?
  - Answer: [Deep RL from Human Preferences](https://outcomeschool.com/blog/decoding-deep-rl-from-human-preferences)
- Why did DPO displace PPO-based RLHF at many labs? When is online RL still better?
  - Answer: [Direct Preference Optimization (DPO)](https://outcomeschool.com/blog/direct-preference-optimization-dpo) and [Proximal Policy Optimization (PPO)](https://outcomeschool.com/blog/proximal-policy-optimization-ppo)
- What is instruction tuning, and why is it important for chat models?
  - Answer: [Decoding InstructGPT](https://outcomeschool.com/blog/decoding-instructgpt)
- How do you prepare a dataset for fine-tuning an LLM?
- What is catastrophic forgetting, and how do you prevent it during fine-tuning?
  - Answer: [Continual Learning in LLMs](https://outcomeschool.com/blog/continual-learning-in-llms)
- When should you choose fine-tuning over RAG over prompt engineering?
  - Answer: Explained in this video: [AI Engineering Explained: LLM, RAG, MCP, Agent, Fine-Tuning, Quantization](https://www.youtube.com/watch?v=lnfWvX66FUk)
- How do you evaluate a fine-tuned model's performance?
  - Answer: [LLM Evaluation](https://outcomeschool.com/blog/llm-evaluation)
- What is synthetic data generation, and how do you use it for fine-tuning?
- What are the key hyperparameters for fine-tuning (learning rate, epochs, batch size, LoRA rank)?
  - Answer: [LoRA - Low-Rank Adaptation of LLMs](https://outcomeschool.com/blog/lora-low-rank-adaptation-of-llms)
- Do the GPU memory math for full fine-tuning a 7B model in bf16 with Adam. Now with LoRA and QLoRA.
- How do you fine-tune a model for a specific domain (legal, medical, finance)?
- What is continual pre-training, and when would you use it?
- How do you merge multiple LoRA adapters?
  - Answer: [LoRA - Low-Rank Adaptation of LLMs](https://outcomeschool.com/blog/lora-low-rank-adaptation-of-llms)
- What is the difference between SFT (Supervised Fine-Tuning) and alignment training?
  - Answer: [Decoding InstructGPT](https://outcomeschool.com/blog/decoding-instructgpt)
- What is RLAIF (RL from AI Feedback), and how does it differ from RLHF?
- What is Constitutional AI, and how does it differ from RLHF?
- What is RLVR (Reinforcement Learning with Verifiable Rewards), and when does it beat a learned reward model?
  - Answer: [Group Relative Policy Optimization (GRPO)](https://outcomeschool.com/blog/group-relative-policy-optimization-grpo)
- What is knowledge distillation for fine-tuning, and what are the legal considerations?
  - Answer: [How does Knowledge Distillation work?](https://outcomeschool.com/blog/how-does-knowledge-distillation-work)
- Your fine-tuned LLM produces factually wrong outputs due to training data quality issues. How do you fix it?
- You must choose between LoRA and full fine-tuning for a domain-specific assistant. How do you decide?
  - Answer: [LoRA - Low-Rank Adaptation of LLMs](https://outcomeschool.com/blog/lora-low-rank-adaptation-of-llms)
- Your fine-tuned model memorized training data verbatim instead of learning patterns. How do you fix overfitting?
- Your fine-tuned LLM forgot its general capabilities after domain-specific fine-tuning. How do you fix catastrophic forgetting?
  - Answer: [Continual Learning in LLMs](https://outcomeschool.com/blog/continual-learning-in-llms)
- Your RLHF preference data has low annotator agreement. How do you ensure data quality?

### Vector Databases and Embeddings

- What are embeddings in the context of AI engineering?
  - Answer: [Embeddings in Machine Learning](https://www.youtube.com/watch?v=LedXW6xl21s)
- How do embedding models convert text to vectors?
  - Answer: [What are Embeddings?](https://outcomeschool.com/blog/what-are-embeddings)
- What is Contrastive Learning, and how is it used to train embedding models?
  - Answer: [What is Contrastive Learning?](https://outcomeschool.com/blog/contrastive-learning)
- What is the difference between sparse and dense embeddings?
- Explain cosine similarity, dot product, and Euclidean distance for vector search.
  - Answer: [How does a Vector Database work?](https://outcomeschool.com/blog/how-does-a-vector-database-work)
- What is a vector database, and how does it differ from a traditional database?
  - Answer: [How does a Vector Database work?](https://outcomeschool.com/blog/how-does-a-vector-database-work)
- How does Approximate Nearest Neighbor (ANN) search work?
  - Answer: [How does Approximate Nearest Neighbor (ANN) search work?](https://outcomeschool.com/blog/how-does-approximate-nearest-neighbor-ann-search-work)
- Compare HNSW, IVF, and flat indexes. How do you pick one, and what does recall@k cost in latency?
  - Answer: [How does Approximate Nearest Neighbor (ANN) search work?](https://outcomeschool.com/blog/how-does-approximate-nearest-neighbor-ann-search-work)
- How does an Embedding Cache work?
  - Answer: [How does an Embedding Cache work?](https://outcomeschool.com/blog/how-does-an-embedding-cache-work)
- How do you choose the right embedding model for your use case?
- What is embedding dimensionality, and how does it affect performance and cost?
- How do you handle embedding drift when the embedding model is updated?
- What are multi-modal embeddings, and how are they generated?
  - Answer: [Multimodal AI](https://outcomeschool.com/blog/multimodal-ai)
- How do you index and query multi-tenant data in a vector database?
- What is quantization of embeddings, and how does it reduce storage costs?
- How do you benchmark and evaluate embedding model quality?
- What is the role of metadata in vector databases?
  - Answer: [How does a Vector Database work?](https://outcomeschool.com/blog/how-does-a-vector-database-work)
- How do you handle large-scale vector search with billions of vectors?
  - Answer: [How does Approximate Nearest Neighbor (ANN) search work?](https://outcomeschool.com/blog/how-does-approximate-nearest-neighbor-ann-search-work)
- What is hybrid search (combining keyword search with vector search)?
  - Answer: [How does Hybrid Search work?](https://outcomeschool.com/blog/how-does-hybrid-search-work)
- How do you fine-tune an embedding model for a specific domain?
  - Answer: [What is Contrastive Learning?](https://outcomeschool.com/blog/contrastive-learning)
- Your vector database for RAG is consuming too much memory. How do you reduce it?
- Your vector database cannot scale to millions of embeddings. How do you fix the bottleneck?
  - Answer: [How does Approximate Nearest Neighbor (ANN) search work?](https://outcomeschool.com/blog/how-does-approximate-nearest-neighbor-ann-search-work)
- Your new embedding model has different dimensions from the existing vectors in production. How do you handle the mismatch?
- Your vector search returns irrelevant results despite high similarity scores. How do you fix it?
- You deployed a new embedding model, and search quality crashed overnight. How do you handle embedding drift?
- Your semantic search fails for short queries. How do you improve it?

### AI System Design

- Design a Real-Time Voice AI Agent
  - Answer: [Design a Real-Time Voice AI Agent](https://outcomeschool.com/blog/design-a-real-time-voice-ai-agent)
- Design ChatGPT: Training to Serving (End to End)
- Design a RAG System (Chat with Your Documents)
- Design an enterprise RAG assistant over 10M documents with per-user permissions.
- Design Memory for a Personal AI Assistant
  - Answer: [AI Agent Memory](https://outcomeschool.com/blog/ai-agent-memory)
- Design a Deep Research Agent
- Design a Multi-Agent Customer Support System
  - Answer: [Multi-Agent Systems](https://outcomeschool.com/blog/multi-agent-systems)
- Design an On-Device AI Assistant
  - Answer: [Cloud vs On-Device Model Deployment](https://outcomeschool.com/blog/cloud-vs-on-device-model-deployment) and [How does llama.cpp run LLMs on everyday hardware?](https://outcomeschool.com/blog/how-does-llama-cpp-run-llms-on-everyday-hardware)
- Design a Multimodal Search System (Text, Image, Video)
- Design an LLM Inference Platform (vLLM-as-a-Service)
  - Answer: [How does vLLM work?](https://outcomeschool.com/blog/how-does-vllm-work) and [LLM Inference Optimization](https://outcomeschool.com/blog/llm-inference-optimization)
- Design an LLM Evaluation Platform
  - Answer: [LLM Evaluation](https://outcomeschool.com/blog/llm-evaluation)
- Design a Text-to-Image Generation Service (Midjourney-like)
- Design a Music Generation Service (Suno-like)
- Design a Video Generation Service (Sora-like)
- Design an AI Coding Agent.
  - Answer: [How does Claude Code work?](https://outcomeschool.com/blog/how-does-claude-code-work) and [How does Cursor work?](https://outcomeschool.com/blog/how-does-cursor-work)
- Design a code generation and review system.
- Design a content moderation system using AI.
- Design a real-time AI recommendation system.
- Design an AI-powered email assistant.
- Design a medical diagnosis assistant using AI.
- Design a fraud detection system powered by LLMs.
- Design an AI-powered data extraction pipeline from unstructured documents.
- Design a Text-to-SQL system over a data warehouse with thousands of tables.
- Design a personalized learning assistant.
- Design an AI system for automated code migration.
- Design an AI-powered legal document review system.
- Design a conversational AI system with memory across sessions.
  - Answer: [AI Agent Memory](https://outcomeschool.com/blog/ai-agent-memory)
- How do you design for latency vs quality trade-offs in AI systems?
- How do you implement caching strategies for LLM applications?
  - Answer: [How does Prompt Caching work?](https://outcomeschool.com/blog/how-does-prompt-caching-work) and [How does Semantic Caching work?](https://outcomeschool.com/blog/how-does-semantic-caching-work)
- How do you design rate limiting and cost management for AI APIs?
- How do you handle failover and fallback strategies for AI systems?
- How do you design an AI system for high availability and fault tolerance?
- How do you design an AI system that gracefully degrades when the model is unavailable?
- What are the key considerations for multi-region deployment of AI systems?
- Design an AI-powered search engine for an e-commerce platform.
- Design an AI gateway/proxy for managing LLM access across an organization.
- How do you design a RAG system that handles conflicting information across sources?
- How do you approach capacity planning for an AI system?
- Design a multi-tenant AI chatbot platform where each business gets a custom chatbot.
- Design an AI meeting summarizer system for thousands of meetings daily.
- Design an AI notification system that prioritizes instead of broadcasting.
- Design an AI-powered anomaly detection system for cloud infrastructure.
- Design an AI-powered document processing pipeline for financial institutions.
- Design an AI dynamic pricing engine.
- Design an AI resume screening system that handles 100K applications per week.
- Design an AI voice assistant architecture.
  - Answer: [Design a Real-Time Voice AI Agent](https://outcomeschool.com/blog/design-a-real-time-voice-ai-agent)
- Design a multi-agent workflow system where agents collaborate on complex tasks.
  - Answer: [Multi-Agent Systems](https://outcomeschool.com/blog/multi-agent-systems)
- Design a real-time AI transcription system for concurrent audio streams.
- Design an AI-powered live streaming content moderation system.

### LLMOps and Production AI

- How does Prompt Caching work?
  - Answer: [How does Prompt Caching work?](https://outcomeschool.com/blog/how-does-prompt-caching-work)
- Prefill vs Decode
  - Answer: [Prefill vs Decode: LLM Inference Optimization](https://outcomeschool.com/blog/prefill-vs-decode-llm-inference-optimization)
- Why is prefill compute-bound and decode memory-bandwidth-bound?
  - Answer: [Prefill vs Decode: LLM Inference Optimization](https://outcomeschool.com/blog/prefill-vs-decode-llm-inference-optimization)
- What is chunked prefill, and why does it improve tail latency under mixed traffic?
  - Answer: [Prefill vs Decode: LLM Inference Optimization](https://outcomeschool.com/blog/prefill-vs-decode-llm-inference-optimization)
- What is Prefill-Decode Disaggregation, and when does it pay off?
  - Answer: [Prefill-Decode Disaggregation in LLM Inference](https://outcomeschool.com/blog/prefill-decode-disaggregation)
- Explain the AI product lifecycle from ideation to production.
- What is LLMOps, and how does it differ from traditional MLOps?
- How do you serve LLMs in production?
  - Answer: [How does vLLM work?](https://outcomeschool.com/blog/how-does-vllm-work) and [LLM Inference Optimization](https://outcomeschool.com/blog/llm-inference-optimization)
- What is model quantization?
  - Answer: Explained in this video: [AI Engineering Explained: LLM, RAG, MCP, Agent, Fine-Tuning, Quantization](https://www.youtube.com/watch?v=lnfWvX66FUk) and [How does Model Quantization work?](https://outcomeschool.com/blog/how-does-model-quantization-work)
- Explain post-training quantization (PTQ) vs quantization-aware training (QAT). What breaks when you push weights to 2-4 bits?
  - Answer: [How does Model Quantization work?](https://outcomeschool.com/blog/how-does-model-quantization-work)
- How do you monitor LLM applications in production?
  - Answer: [AI Agent Observability](https://outcomeschool.com/blog/ai-agent-observability)
- What is LLM observability?
  - Answer: [AI Agent Observability](https://outcomeschool.com/blog/ai-agent-observability)
- What are guardrails for LLMs, and how do you implement them?
  - Answer: [How do LLM guardrails work?](https://outcomeschool.com/blog/how-do-llm-guardrails-work)
- How do you implement content filtering for AI outputs?
  - Answer: [How do LLM guardrails work?](https://outcomeschool.com/blog/how-do-llm-guardrails-work)
- How do you estimate the cost of running an AI-powered feature in production?
- How do you optimize LLM inference costs in production?
  - Answer: [LLM Inference Optimization](https://outcomeschool.com/blog/llm-inference-optimization)
- How do you implement A/B testing for LLM systems?
- What is CI/CD for AI applications, and how does it differ from traditional CI/CD?
- How do you version and manage prompts in production?
- What is model versioning, and how do you handle model rollbacks?
- How do you implement rate limiting and throttling for LLM APIs?
- How do you handle model updates and migrations without downtime?
- What is the role of feature flags in AI deployments?
- How do you implement logging and tracing for LLM applications?
  - Answer: [AI Agent Observability](https://outcomeschool.com/blog/ai-agent-observability)
- How do you handle PII and sensitive data in LLM inputs and outputs?
- What is a gateway pattern for LLM API management?
- How does Token Streaming work?
  - Answer: [How does Token Streaming work?](https://outcomeschool.com/blog/how-does-token-streaming-work)
- How do you implement streaming responses for real-time AI applications?
  - Answer: [How does Token Streaming work?](https://outcomeschool.com/blog/how-does-token-streaming-work)
- How does vLLM work?
  - Answer: [How does vLLM work?](https://outcomeschool.com/blog/how-does-vllm-work)
- How does SGLang work?
  - Answer: [How does SGLang work?](https://outcomeschool.com/blog/how-does-sglang-work)
- How does TensorRT-LLM work?
  - Answer: [How does TensorRT-LLM work?](https://outcomeschool.com/blog/how-does-tensorrt-llm-work)
- How does llama.cpp run LLMs on everyday hardware?
  - Answer: [How does llama.cpp run LLMs on everyday hardware?](https://outcomeschool.com/blog/how-does-llama-cpp-run-llms-on-everyday-hardware)
- When would you choose vLLM vs SGLang vs TensorRT-LLM?
  - Answer: [How does vLLM work?](https://outcomeschool.com/blog/how-does-vllm-work), [How does SGLang work?](https://outcomeschool.com/blog/how-does-sglang-work) and [How does TensorRT-LLM work?](https://outcomeschool.com/blog/how-does-tensorrt-llm-work)
- What are the key SLAs and metrics for production AI systems (latency, throughput, availability)?
- Cloud vs on-device Model Deployment for AI applications.
  - Answer: [Cloud vs On-Device Model Deployment](https://outcomeschool.com/blog/cloud-vs-on-device-model-deployment)
- How do you implement fallback strategies when the primary model is unavailable or rate-limited?
- How do you implement structured output from LLMs reliably in production?
  - Answer: [How does Function Calling work in LLMs?](https://outcomeschool.com/blog/how-does-function-calling-work-in-llms)
- How do you handle long contexts efficiently in production (context compression, prefix caching)?
  - Answer: [How does Prompt Caching work?](https://outcomeschool.com/blog/how-does-prompt-caching-work) and [How does context compaction work?](https://outcomeschool.com/blog/how-does-context-compaction-work)
- What is semantic routing, and how do you implement it in a multi-model system?
  - Answer: [LLM Routing](https://outcomeschool.com/blog/llm-routing)
- How do you manage secrets and API keys securely in LLM applications?
- Your LLM API has latency spikes during peak hours. How do you stabilize it?
- Your LLM endpoint's p99 latency doubled after a deploy with no model change. How do you diagnose it?
- Your LLM costs are too high in production. How do you reduce costs without degrading quality?
  - Answer: [LLM Routing](https://outcomeschool.com/blog/llm-routing) and [How does Semantic Caching work?](https://outcomeschool.com/blog/how-does-semantic-caching-work)
- Your application is hitting LLM provider rate limits during peak hours. How do you handle it?
- Your application depends on one LLM provider. How do you switch providers without downtime?
- Your AI system handles 100 requests/sec but crashes at 5000. How do you scale for concurrent requests?
- A traffic spike brings down your AI system. How do you handle peak traffic?
- One LLM provider outage took down your entire system. How do you eliminate single points of failure?
- Your multi-LLM pipeline fails when one model in the chain breaks. How do you handle orchestration failure?
  - Answer: [AI Orchestration](https://outcomeschool.com/blog/ai-orchestration)
- Your AI pipeline has zero visibility into which step is failing. How do you add observability?
  - Answer: [AI Agent Observability](https://outcomeschool.com/blog/ai-agent-observability)
- You quantized your LLM, but accuracy dropped significantly. How do you minimize quantization loss?
  - Answer: [How does Model Quantization work?](https://outcomeschool.com/blog/how-does-model-quantization-work)
- One failing AI component can take down your entire platform. How do you design graceful degradation?

### Evaluation and Testing

- AI Agent Evaluation
  - Answer: [AI Agent Evaluation](https://outcomeschool.com/blog/ai-agent-evaluation)
- LLM Evaluation
  - Answer: [LLM Evaluation](https://outcomeschool.com/blog/llm-evaluation)
- AI Agent Observability
  - Answer: [AI Agent Observability](https://outcomeschool.com/blog/ai-agent-observability)
- What is evaluation-driven development for AI applications?
- Why is AI only as good as our definition of done?
  - Answer: [AI Is Only as Good as Our Definition of Done](https://outcomeschool.com/blog/ai-is-only-as-good-as-our-definition-of-done)
- How do you evaluate LLM outputs? What metrics do you use?
  - Answer: [LLM Evaluation](https://outcomeschool.com/blog/llm-evaluation)
- Explain BLEU, ROUGE, and BERTScore. When would you use each?
  - Answer: [LLM Evaluation](https://outcomeschool.com/blog/llm-evaluation)
- What is G-Eval, and how does it use LLMs for evaluation?
  - Answer: [LLM as a Judge](https://outcomeschool.com/blog/llm-as-a-judge)
- What is LLM-as-a-judge evaluation, and what are its limitations?
  - Answer: [LLM as a Judge](https://outcomeschool.com/blog/llm-as-a-judge)
- How do you conduct human evaluation for AI systems?
  - Answer: [LLM Evaluation](https://outcomeschool.com/blog/llm-evaluation)
- What is red teaming, and how do you red team an LLM application?
- How do you detect and measure hallucinations in LLM outputs?
- What is adversarial testing for AI systems?
- How do you build a regression test suite for AI applications?
- What are benchmark suites (MMLU, HumanEval, GSM8K), and how do you interpret them?
  - Answer: [LLM Evaluation](https://outcomeschool.com/blog/llm-evaluation)
- What is benchmark contamination, and how do you guard against it?
  - Answer: [LLM Evaluation](https://outcomeschool.com/blog/llm-evaluation)
- Your new model version scores higher on every benchmark, but users say it got worse. Why does this happen, and how do you find the problem?
- How do you evaluate a RAG system end-to-end?
  - Answer: [LLM Evaluation](https://outcomeschool.com/blog/llm-evaluation)
- How do you evaluate the quality of AI agents?
  - Answer: [AI Agent Evaluation](https://outcomeschool.com/blog/ai-agent-evaluation)
- How would you evaluate an autonomous coding agent? Why can SWE-bench pass rates be misleading?
  - Answer: [AI Agent Evaluation](https://outcomeschool.com/blog/ai-agent-evaluation)
- What is the difference between offline and online evaluation for AI systems?
- How do you measure factual consistency in LLM outputs?
- How do you evaluate multi-turn conversation quality?
- What is the role of golden datasets in AI evaluation?
- How do you build an eval set when there is no labelled ground truth and domain experts are expensive?
- How do you implement continuous evaluation for production AI systems?
- How do you evaluate bias in AI model outputs?
- How do you compare two models or prompts in a statistically rigorous way?
- How do you evaluate the robustness of an LLM application across input variations?
- What are the key differences between evaluating traditional ML vs LLM applications?
- How do you set up an evaluation framework from scratch for a new LLM application?
  - Answer: [LLM Evaluation](https://outcomeschool.com/blog/llm-evaluation)
- Your model passes one fairness metric but fails another. How do you handle conflicting audit results?
- Your model was fair at deployment, but became biased 6 months later. How do you monitor continuously?
- An external auditor cannot reproduce your model's results. How do you ensure audit reproducibility?
- How do you structure red teaming for an LLM chatbot before launch?
- How do you red team a multimodal model where text-only safety tests miss cross-modal attacks?

### AI Safety, Ethics, and Responsible AI

- What are hallucinations in LLMs, and how do you mitigate them?
- What is prompt injection, and what are the different types (direct, indirect)?
  - Answer: [Prompt Injection in LLMs](https://outcomeschool.com/blog/prompt-injection-in-llms)
- How do you implement input and output guardrails for AI systems?
  - Answer: [How do LLM guardrails work?](https://outcomeschool.com/blog/how-do-llm-guardrails-work)
- What is AI alignment, and why is it important?
  - Answer: [Decoding InstructGPT](https://outcomeschool.com/blog/decoding-instructgpt) and [Reinforcement Learning from Human Feedback (RLHF)](https://outcomeschool.com/blog/reinforcement-learning-from-human-feedback-rlhf)
- How do you detect and mitigate bias in AI systems?
- What are the key data privacy considerations (GDPR, CCPA) when building AI applications?
- How do you handle PII in LLM inputs and outputs?
- What is explainability in AI, and why does it matter?
- What is the difference between interpretability and explainability?
- What is mechanistic interpretability, and why do AI labs invest in it?
- How do you build trust with users in AI-powered applications?
- What are adversarial attacks on AI systems, and how do you defend against them?
- What is data poisoning, and how can it affect AI models?
- How do you implement content safety filters for AI-generated content?
  - Answer: [How do LLM guardrails work?](https://outcomeschool.com/blog/how-do-llm-guardrails-work)
- What is responsible AI, and what frameworks exist for implementing it?
- How do you handle copyright and intellectual property concerns with AI-generated content?
- What is the EU AI Act, and how does it affect AI engineering?
- How do you implement audit trails and logging for AI decisions?
- What is model card documentation, and why is it important?
- How do you handle misuse and abuse of AI systems in production?
- What is differential privacy, and how can it be applied during model training?
- How would you design an AI incident response plan?
- What is the NIST AI Risk Management Framework (AI RMF)?
- Your healthcare chatbot gives medical diagnoses it should not make. How do you add safety guardrails?
  - Answer: [How do LLM guardrails work?](https://outcomeschool.com/blog/how-do-llm-guardrails-work)
- Your AI system is reproducing copyrighted material verbatim. How do you prevent this?
- Your resume screening AI rejects more female candidates for engineering roles. How do you fix gender bias?
- Your AI model passes bias checks by gender and race separately, but fails for intersectional groups. How do you handle it?
- Your AI denied a loan, and the customer demands a GDPR explanation. How do you provide one?
- A user invokes the right to be forgotten, but their data is in your model weights. How do you comply?
- The EU AI Act may classify your AI system as high-risk. How do you comply?
- Your differentially private model lost significant accuracy. How do you balance privacy and utility?
- One malicious participant is poisoning your federated learning model. How do you defend against it?
- Your AI hiring model uses proxy features for protected attributes. How do you eliminate proxy discrimination?
- Your predictive model creates a feedback loop of biased outcomes. How do you break it?
- Your AI generates fake news images. How do you implement watermarking for AI-generated content?
  - Answer: [How Does LLM Watermarking Work?](https://outcomeschool.com/blog/how-does-llm-watermarking-work)
- Your AI denies a service, and the user has no way to challenge it. How do you design an appeals process?
- An auditor asks why your AI rejected a request 6 months ago, and you have no logs. How do you build audit trails?
- You removed PII, but users were re-identified from anonymized data. How do you prevent re-identification?
- A pre-trained model from an open-source repo may contain a hidden backdoor. How do you detect it?
- Your LLM's training data was deliberately poisoned by an adversary. How do you respond?
- Your AI mental health chatbot gave harmful advice to a user in crisis. How do you mitigate harm?
- Your AI system caused incorrect critical decisions. How do you run a blameless post-mortem?
- Radiologists agree with AI 98% of the time, even when it is wrong. How do you prevent human over-reliance on AI?
- Your content moderation flags normal cultural expressions as offensive in other markets. How do you adapt cross-culturally?
- Your AI training produces massive carbon emissions. How do you reduce environmental impact?

### Multimodal AI

- What are Multimodal AI models, and how do they process different types of data?
  - Answer: [Multimodal AI](https://outcomeschool.com/blog/multimodal-ai)
- How do vision-language models process images?
  - Answer: [Multimodal AI](https://outcomeschool.com/blog/multimodal-ai)
- How do Image Embeddings work?
  - Answer: [How do Image Embeddings work?](https://outcomeschool.com/blog/how-do-image-embeddings-work)
- How does CLIP work, and why is it important for multi-modal AI?
  - Answer: [What is Contrastive Learning?](https://outcomeschool.com/blog/contrastive-learning) and [How do Image Embeddings work?](https://outcomeschool.com/blog/how-do-image-embeddings-work)
- What are the key architectures for multi-modal models?
  - Answer: [Multimodal AI](https://outcomeschool.com/blog/multimodal-ai)
- How does image generation work with diffusion models (Stable Diffusion, DALL-E, Flux)?
  - Answer: [Diffusion Models](https://outcomeschool.com/blog/diffusion-models)
- What is text-to-speech (TTS), and what models are used for it?
- How does speech-to-text (Whisper) work?
- Budget the end-to-end latency for a real-time voice agent (VAD, ASR, LLM, TTS, network). Where does the time go?
  - Answer: [Design a Real-Time Voice AI Agent](https://outcomeschool.com/blog/design-a-real-time-voice-ai-agent)
- How do you handle barge-in (user interruptions) in a voice agent?
  - Answer: [Design a Real-Time Voice AI Agent](https://outcomeschool.com/blog/design-a-real-time-voice-ai-agent)
- Cascaded ASR + LLM + TTS vs native speech-to-speech models: what are the trade-offs?
  - Answer: [Design a Real-Time Voice AI Agent](https://outcomeschool.com/blog/design-a-real-time-voice-ai-agent)
- What is multi-modal RAG, and how does it differ from text-only RAG?
- How do you build a system that processes both images and text?
  - Answer: [Multimodal AI](https://outcomeschool.com/blog/multimodal-ai)
- What are multi-modal embeddings, and how are they used for cross-modal search?
  - Answer: [Multimodal AI](https://outcomeschool.com/blog/multimodal-ai)
- How do you evaluate multi-modal AI systems?
- What are the challenges of real-time multi-modal AI processing?
- How do you handle video understanding with AI?
- What is visual question answering (VQA)?
- What is document understanding, and how do models parse documents with layouts?
- How do you fine-tune a vision-language model?
- What are the latency and cost considerations for multi-modal AI in production?
- How do you handle multi-modal content moderation?
- What is text-to-video generation, and what are the current state-of-the-art approaches?
- Explain Multimodal Fusion Techniques: Early Fusion vs Late Fusion.
- Your vision-language model generates factually incorrect image descriptions. How do you fix it?
- Your VLM answers single-image questions but fails on multi-page documents. How do you fix it?
- Your multimodal LLM ignores the image and generates descriptions from text alone. How do you fix it?
- Your diffusion model ignores precise control requirements in text prompts. How do you improve controllability?
- Your diffusion model generates sharp but repetitive images. How do you balance quality vs diversity?
- Your diffusion model takes too long per image. How do you speed up sampling?

### AI Infrastructure and Scalability

- How do you improve inference speed in production LLM deployments?
  - Answer: [LLM Inference Optimization](https://www.youtube.com/watch?v=jV2sCj4lHYk)
- LLM optimization techniques
  - Answer: [LLM optimization techniques](https://www.linkedin.com/posts/pallavi-shekhar_5-llm-optimization-techniques-lets-understand-activity-7442067281532325888-4aOS)
- How do you select GPUs for LLM inference?
  - Answer: [How does a GPU work for Deep Learning?](https://outcomeschool.com/blog/how-does-a-gpu-work-for-deep-learning)
- How does a GPU work for Deep Learning?
  - Answer: [How does a GPU work for Deep Learning?](https://outcomeschool.com/blog/how-does-a-gpu-work-for-deep-learning)
- How do CUDA Kernels work?
  - Answer: [How do CUDA Kernels work?](https://outcomeschool.com/blog/how-do-cuda-kernels-work)
- How does a Google TPU work?
  - Answer: [How does a Google TPU work?](https://outcomeschool.com/blog/how-does-a-google-tpu-work)
- How does an LPU work?
  - Answer: [How does an LPU work?](https://outcomeschool.com/blog/how-does-an-lpu-work)
- Estimate the GPU memory needed to serve a 70B model (weights, KV cache, activations). Does it fit on a single 80 GB GPU?
- Do the roofline math: how many tokens/sec can one H100 produce for a 70B model at batch size 1?
- What is model parallelism vs data parallelism in distributed training?
- What is tensor parallelism, and how does it help serve large models?
- What is pipeline parallelism?
- How does continuous batching improve LLM inference throughput?
  - Answer: [Continuous Batching in LLMs](https://outcomeschool.com/blog/continuous-batching-in-llms)
- What is speculative decoding, and how does it speed up inference?
  - Answer: [Speculative Decoding](https://outcomeschool.com/blog/speculative-decoding)
- How does Medusa (multi-head speculative decoding) work?
  - Answer: [Medusa - Multi-Head Speculative Decoding](https://outcomeschool.com/blog/decoding-medusa)
- How does EAGLE (feature-level speculative decoding) work?
  - Answer: [EAGLE - Feature-Level Speculative Decoding](https://outcomeschool.com/blog/decoding-eagle)
- What is N-gram Speculation in LLMs, and how does it speed up generation?
  - Answer: [N-gram Speculation in LLMs](https://outcomeschool.com/blog/n-gram-speculation-in-llms)
- What is KV cache, and how do you manage memory for it?
  - Answer: [What is KV Cache in LLMs?](https://outcomeschool.com/blog/kv-cache-in-llms)
- What is Paged Attention?
  - Answer: [Paged Attention in LLMs](https://outcomeschool.com/blog/paged-attention-in-llms)
- How does GGUF work?
  - Answer: [How does GGUF work?](https://outcomeschool.com/blog/how-does-gguf-work)
- How do you optimize inference for edge and mobile deployment?
  - Answer: [How does llama.cpp run LLMs on everyday hardware?](https://outcomeschool.com/blog/how-does-llama-cpp-run-llms-on-everyday-hardware) and [How does Model Quantization work?](https://outcomeschool.com/blog/how-does-model-quantization-work)
- What is model quantization (INT8, INT4, FP16, BF16), and how does it affect quality?
  - Answer: Explained in this video: [AI Engineering Explained: LLM, RAG, MCP, Agent, Fine-Tuning, Quantization](https://www.youtube.com/watch?v=lnfWvX66FUk) and [How does Model Quantization work?](https://outcomeschool.com/blog/how-does-model-quantization-work)
- How do you implement auto-scaling for AI workloads?
- What is the role of load balancing in AI serving infrastructure?
- How do you manage GPU memory for serving multiple models?
- What is model sharding, and when would you use it?
- How do you implement request queuing and priority scheduling for AI services?
- What are the cost trade-offs between self-hosted and API-based AI inference?
- How do you handle cold start latency for serverless AI deployments?
- How do you implement model caching to reduce redundant computations?
  - Answer: [How does Prompt Caching work?](https://outcomeschool.com/blog/how-does-prompt-caching-work)
- What is the difference between synchronous and asynchronous inference, and when do you use each?
- What is FSDP (Fully Sharded Data Parallel), and how does it differ from DeepSpeed ZeRO?
- What are TTFT, TPOT, and throughput, and how do they trade against each other?
  - Answer: [Prefill vs Decode: LLM Inference Optimization](https://outcomeschool.com/blog/prefill-vs-decode-llm-inference-optimization)
- How do you monitor and profile LLM inference in production (TTFT, inter-token latency, GPU utilization)?
- What is model routing at the infrastructure level, and how do you route requests based on complexity and cost?
  - Answer: [LLM Routing](https://outcomeschool.com/blog/llm-routing)

### Coding and Practical Implementation

- Implement a basic RAG pipeline using an embedding model and a vector database.
- Build a simple AI agent with tool use (e.g., calculator, web search).
  - Answer: [ReAct Agent](https://outcomeschool.com/blog/react-agent)
- Implement semantic search using embeddings and cosine similarity.
  - Answer: [How does Semantic Search work?](https://outcomeschool.com/blog/how-does-semantic-search-work) and [How does a Vector Database work?](https://outcomeschool.com/blog/how-does-a-vector-database-work)
- Write code for different text chunking strategies (fixed-size, recursive, semantic).
  - Answer: [Chunking Strategies for RAG](https://outcomeschool.com/blog/chunking-strategies-for-rag)
- Implement a prompt template system with variable substitution.
- Build an evaluation pipeline for LLM outputs using LLM-as-a-judge.
  - Answer: [LLM as a Judge](https://outcomeschool.com/blog/llm-as-a-judge)
- Implement streaming responses for an LLM API.
  - Answer: [How does Token Streaming work?](https://outcomeschool.com/blog/how-does-token-streaming-work)
- Build a simple vector similarity search from scratch.
  - Answer: [How does a Vector Database work?](https://outcomeschool.com/blog/how-does-a-vector-database-work)
- Implement a conversation memory system for a chatbot (sliding window, summary, buffer).
  - Answer: [AI Agent Memory](https://outcomeschool.com/blog/ai-agent-memory)
- Write code to detect and handle hallucinations in LLM outputs.
- Implement a retry mechanism with exponential backoff for LLM API calls.
- Write a function calling (tool use) handler for an LLM API.
  - Answer: [How does Function Calling work in LLMs?](https://outcomeschool.com/blog/how-does-function-calling-work-in-llms)
- Implement a simple re-ranker for search results.
  - Answer: [How does a Reranker work?](https://outcomeschool.com/blog/how-does-a-reranker-work)
- Build a basic document parser that extracts text from PDFs and splits it into chunks.
  - Answer: [Chunking Strategies for RAG](https://outcomeschool.com/blog/chunking-strategies-for-rag)
- Implement cosine similarity, dot product, and Euclidean distance functions from scratch.
  - Answer: [How does a Vector Database work?](https://outcomeschool.com/blog/how-does-a-vector-database-work)
- Write code to implement token counting and context window management.
- Build a simple prompt versioning system.
- Implement a caching layer for LLM responses.
- Implement semantic caching for LLM queries (cache responses for semantically similar queries).
  - Answer: [How does Semantic Caching work?](https://outcomeschool.com/blog/how-does-semantic-caching-work)
- Write code to detect prompt injection attempts in user inputs.
  - Answer: [Prompt Injection in LLMs](https://outcomeschool.com/blog/prompt-injection-in-llms)
- Implement an LLM output guardrails system that checks for off-topic responses and PII leakage.
  - Answer: [How do LLM guardrails work?](https://outcomeschool.com/blog/how-do-llm-guardrails-work)
- Build a multi-agent system where agents have different roles and collaborate on a task.
  - Answer: [Multi-Agent Systems](https://outcomeschool.com/blog/multi-agent-systems)
- Implement scaled dot-product attention with a causal mask from scratch (NumPy or PyTorch).
  - Answer: [Math behind Attention - Q, K, and V](https://outcomeschool.com/blog/math-behind-attention-qkv) and [Causal Masking in Attention](https://outcomeschool.com/blog/causal-masking-in-attention)
- Implement multi-head attention, then convert it to grouped-query attention.
  - Answer: [Multi-Head Attention in Transformers](https://outcomeschool.com/blog/multi-head-attention-in-transformers) and [Grouped Query Attention](https://outcomeschool.com/blog/grouped-query-attention)
- Implement a KV cache and single-step decode for causal multi-head attention.
  - Answer: [What is KV Cache in LLMs?](https://outcomeschool.com/blog/kv-cache-in-llms)
- Implement BPE (Byte Pair Encoding) training and encoding from scratch.
  - Answer: [Byte Pair Encoding](https://outcomeschool.com/blog/bpe-in-llms)
- Implement top-k, top-p, and temperature sampling over a logits vector.
- Implement an LRU cache with O(1) get/put, then add per-entry TTL.
- Implement a token-bucket rate limiter for an LLM API where cost scales with tokens, then make it distributed.
- Write an async batch processor that runs an LLM call over 50,000 documents with a concurrency limit, retries with jitter, and error isolation.
- Write a streaming SSE parser for LLM token streams that handles arbitrary chunk boundaries.
  - Answer: [How does Token Streaming work?](https://outcomeschool.com/blog/how-does-token-streaming-work)
- Implement a minimal agent loop with tool dispatch, error handling, and a step budget.
  - Answer: [AI Agent Loop](https://outcomeschool.com/blog/ai-agent-loop)

### Behavioral and Scenario-Based Questions

- What is AI Engineering, and how does it differ from Machine Learning Engineering?
- How do you decide whether a problem needs AI or a traditional software solution?
- How do you measure the ROI of an AI feature?
- How do you handle hallucinations when they occur in a production AI system?
- How do you decide between using an LLM API vs self-hosting an open-source model?
- How do you manage stakeholder expectations for AI projects?
- Describe your approach to debugging a poor-performing RAG system.
- How do you stay current with the rapidly evolving AI landscape?
- How do you balance innovation with reliability in AI systems?
- Tell me about a challenging AI project you worked on. What was the problem? What approach did you take? What trade-offs did you make? What was the outcome?
- How would you handle a situation where an AI model produces biased or harmful outputs in production?
- How do you approach cost optimization for an AI system that's exceeding budget?
- Describe a time when you had to choose between model accuracy and latency. How did you make the decision?
- How would you handle a situation where your AI system's quality degrades over time?
- How do you communicate AI limitations to non-technical stakeholders?
- How would you approach building an AI feature with limited labeled data?
- Describe your experience working with cross-functional teams on AI projects.
- Where do you see AI engineering heading in the next 3-5 years?
- Why are you interested in this AI engineering role?
- Your PM wants to ship an AI feature with a 15% hallucination rate on edge cases. How do you communicate the risk?
- A non-technical executive asks why your AI feature cannot be 100% accurate. How do you explain LLM limitations?
- You need to choose between a complex agentic system that scores 15% better on benchmarks, or a simpler RAG pipeline that is easier to maintain. How do you decide?

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
