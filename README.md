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
- [GitHub](http://github.com/OutcomeSchool)

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


## 📖 Quick Reference

> One-liner definitions to orient you before diving into the questions.

| Term | Definition |
|---|---|
| **LLM** | Neural network trained on vast text to generate and understand language |
| **RAG** | Augmenting LLM responses by retrieving relevant context from an external knowledge base |
| **Agent** | An LLM-powered system using tools, memory, and reasoning to complete tasks autonomously |
| **MCP** | Model Context Protocol — a standard for connecting LLMs to external tools and data sources |
| **Fine-tuning** | Further training a pre-trained model on domain-specific data to adapt its behaviour |
| **LoRA** | PEFT method that adds low-rank weight matrices instead of updating all parameters |
| **Quantization** | Reducing weight precision (e.g. FP32→INT4) to shrink model size and speed up inference |
| **KV Cache** | Storing key/value attention states to avoid recomputing them on every new token |
| **Embeddings** | Dense vector representations of text that encode semantic meaning |
| **Vector Database** | Database optimised for storing and querying high-dimensional embedding vectors |
| **Prompt Engineering** | Crafting inputs to steer LLM behaviour without changing model weights |
| **Guardrails** | Input/output filters that prevent harmful, off-topic, or unsafe model responses |

**Difficulty legend:** 🟢 Beginner &nbsp;·&nbsp; 🟡 Intermediate &nbsp;·&nbsp; 🔴 Advanced &nbsp;·&nbsp; ✅ Answered &nbsp;·&nbsp; 🔲 Open

---

### LLM Fundamentals

- ✅ 🟢 `[Beginner]` What are foundation models, and how have they changed AI engineering?
  <details>
  <summary>💡 Answer</summary>

  Explained in this video: [AI Engineering Explained: LLM, RAG, MCP, Agent, Fine-Tuning, Quantization](https://www.youtube.com/watch?v=lnfWvX66FUk)

  </details>
- ✅ 🟢 `[Beginner]` What is a Large Language Model (LLM), and how does it work?
  <details>
  <summary>💡 Answer</summary>

  Explained in this video: [AI Engineering Explained: LLM, RAG, MCP, Agent, Fine-Tuning, Quantization](https://www.youtube.com/watch?v=lnfWvX66FUk)

  </details>
- ✅ 🟢 `[Beginner]` Inside ChatGPT: What Happens After You Hit Enter?
  <details>
  <summary>💡 Answer</summary>

  [Inside ChatGPT: What Happens After You Hit Enter](https://outcomeschool.substack.com/p/inside-chatgpt-what-happens-after)

  </details>
- ✅ 🟢 `[Beginner]` What is the Transformer architecture and how does it work?
  <details>
  <summary>💡 Answer</summary>

  [Decoding Transformer Architecture](https://outcomeschool.com/blog/decoding-transformer-architecture)

  </details>
- ✅ 🟢 `[Beginner]` What are the key components of the Transformer architecture?
  <details>
  <summary>💡 Answer</summary>

  [Decoding Transformer Architecture](https://outcomeschool.com/blog/decoding-transformer-architecture)

  </details>
- ✅ 🟢 `[Beginner]` What is tokenization in LLMs?
  <details>
  <summary>💡 Answer</summary>

  [Tokenization in Large Language Models (LLMs)](https://www.youtube.com/watch?v=sK2s9I84EVI)

  </details>
- ✅ 🟡 `[Intermediate]` Explain BPE (Byte Pair Encoding).
  <details>
  <summary>💡 Answer</summary>

  [Byte Pair Encoding](https://outcomeschool.com/blog/bpe-in-llms)

  </details>
- 🔲 🟡 `[Intermediate]` Explain WordPiece and SentencePiece.
- ✅ 🟢 `[Beginner]` What is positional encoding, and why is it needed in Transformers?
  <details>
  <summary>💡 Answer</summary>

  [Positional Embeddings in LLMs](https://outcomeschool.substack.com/p/positional-embeddings-in-llms)

  </details>
- ✅ 🟢 `[Beginner]` What are embeddings?
  <details>
  <summary>💡 Answer</summary>

  [Embeddings in Machine Learning](https://www.youtube.com/watch?v=LedXW6xl21s)

  </details>
- ✅ 🟡 `[Intermediate]` Explain the Query(Q), Key(K), and Value(V) in attention.
  <details>
  <summary>💡 Answer</summary>

  [Math behind Attention - Q, K, and V](https://outcomeschool.com/blog/math-behind-attention-qkv)

  </details>
- ✅ 🟢 `[Beginner]` What is self-attention, and how does it work in Transformers?
  <details>
  <summary>💡 Answer</summary>

  [Self Attention in Transformers](https://outcomeschool.com/blog/self-attention-in-transformers)

  </details>
- ✅ 🟢 `[Beginner]` What is Cross Attention in Transformers?
  <details>
  <summary>💡 Answer</summary>

  [Cross Attention in Transformers](https://outcomeschool.com/blog/cross-attention-in-transformers)

  </details>
- ✅ 🔴 `[Advanced]` Why do we scale the dot product attention by √dₖ in the Transformer architecture?
  <details>
  <summary>💡 Answer</summary>

  [Math behind √dₖ Scaling Factor in Attention](https://outcomeschool.com/blog/scaling-dot-product-attention)

  </details>
- ✅ 🟢 `[Beginner]` What is causal masking?
  <details>
  <summary>💡 Answer</summary>

  [Causal Masking in Attention](https://outcomeschool.com/blog/causal-masking-in-attention)

  </details>
- ✅ 🟢 `[Beginner]` What are multi-head attention mechanisms? Why use multiple attention heads?
  <details>
  <summary>💡 Answer</summary>

  [Multi-Head Attention in Transformers](https://outcomeschool.com/blog/multi-head-attention-in-transformers)

  </details>
- ✅ 🟢 `[Beginner]` What are Feed-Forward Networks in LLMs?
  <details>
  <summary>💡 Answer</summary>

  [Feed-Forward Networks in LLMs](https://outcomeschool.com/blog/feed-forward-networks-in-llms)

  </details>
- ✅ 🟢 `[Beginner]` What is the context window in LLMs, and why does it matter?
  <details>
  <summary>💡 Answer</summary>

  [Context Window in LLMs](https://www.linkedin.com/posts/amit-shekhar-iitbhu_the-context-window-is-the-llms-working-memory-activity-7437754426175672320-MH9c)

  </details>
- ✅ 🟢 `[Beginner]` Why is the context window limited in LLMs?
  <details>
  <summary>💡 Answer</summary>

  [Why is the context window limited in LLMs?](https://www.youtube.com/watch?v=CGIhxIaOg3M&lc)

  </details>
- ✅ 🟢 `[Beginner]` What is temperature in the context of LLMs, and how does it affect output?
  <details>
  <summary>💡 Answer</summary>

  [What is temperature in the context of LLMs?](https://x.com/amitiitbhu/status/1964990603927687493)

  </details>
- ✅ 🟢 `[Beginner]` Why is the first token slower than the rest in an LLM?
  <details>
  <summary>💡 Answer</summary>

  [The First-Token Latency Problem in LLMs](https://www.youtube.com/watch?v=XD8DD4cEHu0)

  </details>
- 🔲 🟡 `[Intermediate]` Explain Top-p (nucleus) sampling and Top-k sampling. How do they differ?
- ✅ 🟢 `[Beginner]` What are logits, and how are they used in text generation?
  <details>
  <summary>💡 Answer</summary>

  [Understanding Logits in Machine Learning](https://x.com/amitiitbhu/status/1927927814923207146)

  </details>
- ✅ 🟢 `[Beginner]` What are skip connections (residual connections) in Transformers?
  <details>
  <summary>💡 Answer</summary>

  [Skip connections (residual connections) in Transformers](https://www.linkedin.com/posts/amit-shekhar-iitbhu_machinelearning-llm-deeplearning-share-7414239846707392512-pQdQ)

  </details>
- 🔲 🟢 `[Beginner]` What is the difference between open-source and closed-source LLMs? When would you choose one over the other?
- ✅ 🟢 `[Beginner]` What is the difference between encoder-only, decoder-only, and encoder-decoder Transformer architectures?
  <details>
  <summary>💡 Answer</summary>

  [Decoding Transformer Architecture](https://outcomeschool.com/blog/decoding-transformer-architecture)

  </details>
- ✅ 🟢 `[Beginner]` What is KV cache, and how does it speed up inference?
  <details>
  <summary>💡 Answer</summary>

  [What is KV Cache in LLMs?](https://outcomeschool.com/blog/kv-cache-in-llms)

  </details>
- ✅ 🟢 `[Beginner]` What is model distillation, and how is it used with LLMs?
  <details>
  <summary>💡 Answer</summary>

  [How does Knowledge Distillation work?](https://outcomeschool.com/blog/how-does-knowledge-distillation-work)

  </details>
- ✅ 🟡 `[Intermediate]` What is Mixture of Experts (MoE), and how does it work in models like Mixtral?
  <details>
  <summary>💡 Answer</summary>

  [Mixture of Experts Explained](https://outcomeschool.com/blog/mixture-of-experts)

  </details>
- ✅ 🟢 `[Beginner]` What is the difference between dense and sparse models?
  <details>
  <summary>💡 Answer</summary>

  [Mixture of Experts Explained](https://outcomeschool.com/blog/mixture-of-experts)

  </details>
- ✅ 🟢 `[Beginner]` What is Flash Attention?
  <details>
  <summary>💡 Answer</summary>

  [Decoding Flash Attention in LLMs](https://outcomeschool.com/blog/decoding-flash-attention)

  </details>
- ✅ 🟢 `[Beginner]` What is Cross-Entropy Loss?
  <details>
  <summary>💡 Answer</summary>

  [Math Behind Cross-Entropy Loss](https://outcomeschool.com/blog/math-behind-cross-entropy-loss)

  </details>
- ✅ 🟡 `[Intermediate]` What is Grouped-Query Attention (GQA), and how does it differ from Multi-Head Attention (MHA)?
  <details>
  <summary>💡 Answer</summary>

  [Grouped Query Attention](https://outcomeschool.com/blog/grouped-query-attention)

  </details>
- ✅ 🟡 `[Intermediate]` How does Rotary Position Embedding (RoPE) work, and why is it preferred over learned positional embeddings?
  <details>
  <summary>💡 Answer</summary>

  [Math Behind RoPE (Rotary Position Embedding)](https://outcomeschool.com/blog/math-behind-rope-rotary-position-embedding)

  </details>
- ✅ 🟡 `[Intermediate]` Explain Layer Normalization
  <details>
  <summary>💡 Answer</summary>

  [Batch Normalization vs Layer Normalization](https://outcomeschool.com/blog/batch-normalization-vs-layer-normalization)

  </details>
- ✅ 🟡 `[Intermediate]` Explain RMSNorm (Root Mean Square Layer Normalization)
  <details>
  <summary>💡 Answer</summary>

  [RMSNorm (Root Mean Square Layer Normalization)](https://outcomeschool.com/blog/rmsnorm-root-mean-square-layer-normalization)

  </details>
- 🔲 🔴 `[Advanced]` Your LLM keeps ignoring your instructions. How do you make it follow structured output formats?
- 🔲 🔴 `[Advanced]` Your LLM-powered tool hits the context window limit on long documents. How do you handle it?
- 🔲 🔴 `[Advanced]` Your LLM does not admit when it does not know the answer. How do you make it say "I don't know"?
- 🔲 🔴 `[Advanced]` Your LLM generates responses that are too verbose. How do you control response length?
- 🔲 🔴 `[Advanced]` Your LLM memorized proprietary training data and leaks it in responses. How do you prevent this?
- 🔲 🔴 `[Advanced]` Your LLM coding assistant generates outdated code using deprecated libraries. How do you fix it?
- 🔲 🔴 `[Advanced]` Your tokenizer splits important domain terms into meaningless subword pieces. How do you fix it?
- ✅ 🔴 `[Advanced]` Your Transformer's KV cache grows too large during long sequence generation. How do you manage memory?
  <details>
  <summary>💡 Answer</summary>

  [Paged Attention in LLMs](https://outcomeschool.com/blog/paged-attention-in-llms)

  </details>
- 🔲 🔴 `[Advanced]` Your Transformer runs out of memory on long documents due to quadratic self-attention. How do you scale it?
- 🔲 🔴 `[Advanced]` Your distilled student model fails on the complex reasoning that the teacher model handled. How do you close the gap?
- 🔲 🟡 `[Intermediate]` After RLHF alignment, your LLM became safer but lost capability on hard tasks. How do you manage the alignment tax?
- ✅ 🔴 `[Advanced]` Your RLHF-trained LLM is gaming the reward model instead of being genuinely helpful. How do you fix reward hacking?
  <details>
  <summary>💡 Answer</summary>

  [Reinforcement Learning from Human Feedback (RLHF)](https://outcomeschool.com/blog/reinforcement-learning-from-human-feedback-rlhf)

  </details>
- ✅ 🔴 `[Advanced]` Your chatbot loses context after 10 turns in a conversation. How do you maintain a long conversation context?
  <details>
  <summary>💡 Answer</summary>

  [AI Agent Memory](https://outcomeschool.com/blog/ai-agent-memory)

  </details>
- 🔲 🔴 `[Advanced]` Your chatbot fails when users switch topics mid-conversation. How do you handle topic switches?
- 🔲 🔴 `[Advanced]` Your QA system always generates an answer even when no answer exists in the context. How do you detect unanswerable questions?
- 🔲 🔴 `[Advanced]` Your summarization system hallucinated facts not in the original article. How do you fix it?
- 🔲 🔴 `[Advanced]` Your text generation repeats phrases in long outputs. How do you fix repetition?
- ✅ 🟢 `[Beginner]` Transformers work on text, so can they also understand images?
  <details>
  <summary>💡 Answer</summary>

  [Decoding Vision Transformer (ViT)](https://outcomeschool.com/blog/decoding-vision-transformer-vit)

  </details>
- ✅ 🟢 `[Beginner]` Small Language Models (SLMs)
  <details>
  <summary>💡 Answer</summary>

  [Small Language Models (SLMs)](https://outcomeschool.com/blog/small-language-models-slms)

  </details>
- ✅ 🟢 `[Beginner]` Large Reasoning Models (LRMs)
  <details>
  <summary>💡 Answer</summary>

  [Large Reasoning Models (LRMs)](https://outcomeschool.com/blog/large-reasoning-models)

  </details>
- ✅ 🟢 `[Beginner]` What are Autoregressive Models?
  <details>
  <summary>💡 Answer</summary>

  [Autoregressive Models](https://outcomeschool.com/blog/autoregressive-models)

  </details>
- 🔲 🟡 `[Intermediate]` Explain the difference between autoregressive and masked language modeling.
- ✅ 🟢 `[Beginner]` Proximal Policy Optimization (PPO)
  <details>
  <summary>💡 Answer</summary>

  [Proximal Policy Optimization (PPO)](https://outcomeschool.com/blog/proximal-policy-optimization-ppo)

  </details>
- ✅ 🟢 `[Beginner]` Direct Preference Optimization (DPO)
  <details>
  <summary>💡 Answer</summary>

  [Direct Preference Optimization (DPO)](https://outcomeschool.com/blog/direct-preference-optimization-dpo)

  </details>
- ✅ 🟢 `[Beginner]` Group Relative Policy Optimization (GRPO)
  <details>
  <summary>💡 Answer</summary>

  [Group Relative Policy Optimization (GRPO)](https://outcomeschool.com/blog/group-relative-policy-optimization-grpo)

  </details>
- ✅ 🟢 `[Beginner]` Recursive Language Models (RLMs)
  <details>
  <summary>💡 Answer</summary>

  [Recursive Language Models (RLMs)](https://outcomeschool.com/blog/recursive-language-models)

  </details>
- ✅ 🟢 `[Beginner]` Continual Learning in LLMs
  <details>
  <summary>💡 Answer</summary>

  [Continual Learning in LLMs](https://outcomeschool.com/blog/continual-learning-in-llms)

  </details>
- ✅ 🟡 `[Intermediate]` How do Diffusion Language Models (DLMs) work?
  <details>
  <summary>💡 Answer</summary>

  [How do Diffusion Language Models (DLMs) work?](https://outcomeschool.com/blog/how-do-diffusion-language-models-dlms-work)

  </details>

### Prompt Engineering

- 🔲 🟢 `[Beginner]` What is prompt engineering, and why is it critical for AI applications?
- ✅ 🟡 `[Intermediate]` Explain zero-shot, one-shot, and few-shot prompting with examples.
  <details>
  <summary>💡 Answer</summary>

  [Explain zero-shot, one-shot, and few-shot prompting with examples](https://www.linkedin.com/posts/pallavi-shekhar_llm-prompting-ai-activity-7441801012472078336-JsHr)

  </details>
- ✅ 🟢 `[Beginner]` What is chain-of-thought (CoT) prompting, and when should you use it?
  <details>
  <summary>💡 Answer</summary>

  [How does Chain-of-Thought (CoT) Prompting work?](https://outcomeschool.com/blog/how-does-chain-of-thought-prompting-work)

  </details>
- 🔲 🟡 `[Intermediate]` Explain self-consistency prompting and how it improves reasoning.
- 🔲 🟢 `[Beginner]` What is tree-of-thought prompting?
- ✅ 🟢 `[Beginner]` What is ReAct (Reasoning + Acting) prompting, and how does it work?
  <details>
  <summary>💡 Answer</summary>

  [ReAct Agent](https://outcomeschool.com/blog/react-agent)

  </details>
- 🔲 🟢 `[Beginner]` What is a system prompt, and how does it influence model behavior?
- 🔲 🟡 `[Intermediate]` How do you structure prompts for consistent structured output (JSON, XML)?
- 🔲 🟢 `[Beginner]` What is prompt injection, and how do you defend against it?
- 🔲 🟢 `[Beginner]` What is jailbreaking in LLMs, and what are common jailbreak techniques?
- 🔲 🟡 `[Intermediate]` How do you optimize prompts for cost and latency?
- 🔲 🟢 `[Beginner]` What is the difference between prompt engineering and prompt tuning?
- 🔲 🔴 `[Advanced]` What is a prompt template, and how do you design one for production use?
- 🔲 🟡 `[Intermediate]` How do you handle multi-turn conversations with LLMs?
- 🔲 🟢 `[Beginner]` What is role prompting, and when is it effective?
- ✅ 🟢 `[Beginner]` What is prompt chaining, and how do you design a chain of prompts for complex tasks?
  <details>
  <summary>💡 Answer</summary>

  [How does Prompt Chaining work?](https://outcomeschool.com/blog/how-does-prompt-chaining-work)

  </details>
- 🔲 🟡 `[Intermediate]` How do you evaluate and iterate on prompt quality?
- 🔲 🟢 `[Beginner]` What are meta-prompts, and how can they be used to generate prompts?
- 🔲 🟢 `[Beginner]` What are the common failure modes in prompting, and how do you debug them?
- 🔲 🟡 `[Intermediate]` How do you handle edge cases and adversarial inputs in prompt design?
- 🔲 🟢 `[Beginner]` What is the "lost in the middle" problem in long-context prompting?
- 🔲 🔴 `[Advanced]` What are output parsers, and why are they needed for production applications?
- 🔲 🟡 `[Intermediate]` How do you handle multi-language prompting effectively?
- 🔲 🔴 `[Advanced]` Your few-shot prompting gives inconsistent results across similar inputs. How do you stabilize it?
- 🔲 🔴 `[Advanced]` Your LLM classification system is too sensitive to prompt wording changes. How do you reduce prompt sensitivity?
- 🔲 🔴 `[Advanced]` Your chatbot's system prompt containing proprietary business logic is being leaked by users. How do you prevent it?
- 🔲 🔴 `[Advanced]` Your LLM agent is vulnerable to prompt injection that reveals the system prompt. How do you defend it?
- 🔲 🔴 `[Advanced]` Your chain-of-thought prompting is not improving LLM accuracy on reasoning tasks. What do you fix?
- 🔲 🔴 `[Advanced]` Your AI system works in English but fails for other languages. How do you add multilingual support?
- 🔲 🔴 `[Advanced]` Your zero-shot cross-lingual transfer from English fails on other languages. How do you fix it?

### Retrieval-Augmented Generation (RAG)

- ✅ 🟢 `[Beginner]` What is Retrieval-Augmented Generation (RAG), and why is it important?
  <details>
  <summary>💡 Answer</summary>

  Explained in this video: [AI Engineering Explained: LLM, RAG, MCP, Agent, Fine-Tuning, Quantization](https://www.youtube.com/watch?v=lnfWvX66FUk)

  </details>
- ✅ 🟡 `[Intermediate]` Explain the architecture of a basic RAG system.
  <details>
  <summary>💡 Answer</summary>

  Explained in this video: [AI Engineering Explained: LLM, RAG, MCP, Agent, Fine-Tuning, Quantization](https://www.youtube.com/watch?v=lnfWvX66FUk)

  </details>
- ✅ 🟢 `[Beginner]` What are the key components of a RAG pipeline?
  <details>
  <summary>💡 Answer</summary>

  Explained in this video: [AI Engineering Explained: LLM, RAG, MCP, Agent, Fine-Tuning, Quantization](https://www.youtube.com/watch?v=lnfWvX66FUk)

  </details>
- 🔲 🟢 `[Beginner]` What are chunking strategies, and how do you choose the right chunk size?
- 🔲 🟡 `[Intermediate]` Compare fixed-size chunking, semantic chunking, and recursive chunking.
- ✅ 🟢 `[Beginner]` What are embedding models, and how do they convert text to vectors?
  <details>
  <summary>💡 Answer</summary>

  [What are Embeddings?](https://outcomeschool.com/blog/what-are-embeddings)

  </details>
- 🔲 🟡 `[Intermediate]` How do you choose an embedding model for your RAG system?
- ✅ 🟡 `[Intermediate]` Explain Agentic RAG.
  <details>
  <summary>💡 Answer</summary>

  [Agentic RAG](https://outcomeschool.com/blog/agentic-rag)

  </details>
- ✅ 🟢 `[Beginner]` What is hybrid search, and why is it better than pure vector search?
  <details>
  <summary>💡 Answer</summary>

  [How does Hybrid Search work?](https://outcomeschool.com/blog/how-does-hybrid-search-work)

  </details>
- ✅ 🟢 `[Beginner]` What is re-ranking, and how does it improve RAG retrieval quality?
  <details>
  <summary>💡 Answer</summary>

  [How does a Reranker work?](https://outcomeschool.com/blog/how-does-a-reranker-work)

  </details>
- 🔲 🟡 `[Intermediate]` How do you handle multi-document and multi-hop questions in RAG?
- 🔲 🟢 `[Beginner]` What is the "lost in the middle" problem in RAG systems?
- 🔲 🟡 `[Intermediate]` How do you evaluate a RAG system? Explain faithfulness, relevance, and context precision/recall.
- 🔲 🟡 `[Intermediate]` Explain Self-RAG. How does the model decide when to retrieve?
- ✅ 🟢 `[Beginner]` What is GraphRAG, and when would you use it over traditional RAG?
  <details>
  <summary>💡 Answer</summary>

  [GraphRAG](https://outcomeschool.com/blog/graphrag)

  </details>
- 🔲 🟡 `[Intermediate]` How do you handle structured data (tables, SQL databases) in a RAG pipeline?
- 🔲 🟢 `[Beginner]` What are the common failure modes of RAG systems, and how do you debug them?
- 🔲 🟡 `[Intermediate]` How do you handle document updates and maintain freshness in a RAG system?
- 🔲 🔴 `[Advanced]` How do you optimize RAG for latency in production?
- 🔲 🟢 `[Beginner]` What is the role of metadata filtering in RAG systems?
- ✅ 🟡 `[Intermediate]` Compare RAG vs fine-tuning. When would you use each?
  <details>
  <summary>💡 Answer</summary>

  Explained in this video: [AI Engineering Explained: LLM, RAG, MCP, Agent, Fine-Tuning, Quantization](https://www.youtube.com/watch?v=lnfWvX66FUk)

  </details>
- ✅ 🟢 `[Beginner]` What is query transformation in RAG (HyDE, query decomposition, step-back prompting)?
  <details>
  <summary>💡 Answer</summary>

  [How does HyDE work in RAG?](https://outcomeschool.com/blog/how-does-hyde-work)

  </details>
- 🔲 🟡 `[Intermediate]` How do you implement citation and source attribution in RAG?
- 🔲 🔴 `[Advanced]` How do you scale a RAG system to millions of documents?
- 🔲 🟢 `[Beginner]` What is parent-child chunking, and how does it improve retrieval?
- 🔲 🔴 `[Advanced]` Your RAG system is hallucinating despite having the right context. How do you fix it?
- 🔲 🔴 `[Advanced]` Your RAG chunk overlap causes redundant results. How do you reduce redundancy?
- 🔲 🔴 `[Advanced]` Your RAG retrieval is too slow with a large knowledge base. How do you speed it up?
- 🔲 🔴 `[Advanced]` Your RAG system returns duplicate results. How do you deduplicate?
- 🔲 🔴 `[Advanced]` Your RAG system needs per-user access control on internal documents. How do you implement it?
- 🔲 🔴 `[Advanced]` Your RAG system fails on domain-specific jargon. How do you fix it?
- 🔲 🔴 `[Advanced]` Your text-only RAG system now needs to handle images and tables. How do you extend it?
- 🔲 🔴 `[Advanced]` Your RAG knowledge base gets updated frequently and needs versioning. How do you manage it?
- 🔲 🔴 `[Advanced]` Your RAG system fails on multi-hop questions that require combining multiple facts. How do you fix it?
- 🔲 🔴 `[Advanced]` Your enterprise RAG system returns contradictory answers from different source documents. How do you resolve conflicts?
- 🔲 🔴 `[Advanced]` Your RAG system returns outdated answers from an evolving knowledge base. How do you keep it current?
- 🔲 🔴 `[Advanced]` Your RAG system struggles with PDF documents containing tables and layouts. How do you fix PDF parsing?

### AI Agents and Agentic Systems

- ✅ 🟢 `[Beginner]` What is an AI agent, and how does it differ from a simple LLM call?
  <details>
  <summary>💡 Answer</summary>

  Explained in this video: [AI Engineering Explained: LLM, RAG, MCP, Agent, Fine-Tuning, Quantization](https://www.youtube.com/watch?v=lnfWvX66FUk) and [AI Agent Explained](https://outcomeschool.com/blog/ai-agent)

  </details>
- ✅ 🟡 `[Intermediate]` AI Agent Memory
  <details>
  <summary>💡 Answer</summary>

  [AI Agent Memory](https://outcomeschool.com/blog/ai-agent-memory)

  </details>
- ✅ 🟡 `[Intermediate]` Harness Engineering in AI
  <details>
  <summary>💡 Answer</summary>

  [Harness Engineering in AI](https://outcomeschool.com/blog/harness-engineering-in-ai)

  </details>
- ✅ 🟡 `[Intermediate]` Explain the ReAct (Reasoning + Acting) agent architecture.
  <details>
  <summary>💡 Answer</summary>

  [ReAct Agent](https://outcomeschool.com/blog/react-agent)

  </details>
- ✅ 🟢 `[Beginner]` What is the Plan-and-Execute agent pattern?
  <details>
  <summary>💡 Answer</summary>

  [Plan-and-Execute Agent](https://outcomeschool.com/blog/plan-and-execute-agent)

  </details>
- ✅ 🟢 `[Beginner]` What is tool use (function calling) in LLMs, and how does it enable agents?
  <details>
  <summary>💡 Answer</summary>

  Explained in this video: [AI Engineering Explained: LLM, RAG, MCP, Agent, Fine-Tuning, Quantization](https://www.youtube.com/watch?v=lnfWvX66FUk)

  </details>
- ✅ 🟡 `[Intermediate]` How do you design and define tools for an AI agent?
  <details>
  <summary>💡 Answer</summary>

  Explained in this video: [AI Engineering Explained: LLM, RAG, MCP, Agent, Fine-Tuning, Quantization](https://www.youtube.com/watch?v=lnfWvX66FUk)

  </details>
- ✅ 🟢 `[Beginner]` What is the difference between single-agent and multi-agent systems?
  <details>
  <summary>💡 Answer</summary>

  [Multi-Agent Systems](https://outcomeschool.com/blog/multi-agent-systems)

  </details>
- ✅ 🟢 `[Beginner]` What is Model Context Protocol (MCP), and how does it standardize tool integration?
  <details>
  <summary>💡 Answer</summary>

  Explained in this video: [AI Engineering Explained: LLM, RAG, MCP, Agent, Fine-Tuning, Quantization](https://www.youtube.com/watch?v=lnfWvX66FUk)

  </details>
- ✅ 🟢 `[Beginner]` What are AI SubAgents?
  <details>
  <summary>💡 Answer</summary>

  [AI SubAgents](https://outcomeschool.com/blog/ai-subagents)

  </details>
- ✅ 🟢 `[Beginner]` What are the different types of agent memory (short-term, long-term, episodic)?
  <details>
  <summary>💡 Answer</summary>

  [AI Agent Memory](https://outcomeschool.com/blog/ai-agent-memory)

  </details>
- 🔲 🟡 `[Intermediate]` How do you handle agent failures and implement error recovery?
- ✅ 🟢 `[Beginner]` What is an agent loop, and how does it decide when to stop?
  <details>
  <summary>💡 Answer</summary>

  [AI Agent Loop](https://outcomeschool.com/blog/ai-agent-loop)

  </details>
- ✅ 🟡 `[Intermediate]` Context Engineering
  <details>
  <summary>💡 Answer</summary>

  [Context Engineering](https://outcomeschool.com/blog/context-engineering)

  </details>
- ✅ 🟡 `[Intermediate]` How does context compaction work?
  <details>
  <summary>💡 Answer</summary>

  [How does context compaction work?](https://outcomeschool.com/blog/how-does-context-compaction-work) 

  </details>
- ✅ 🟡 `[Intermediate]` How AI Agents Communicate?
  <details>
  <summary>💡 Answer</summary>

  [How AI Agents Communicate](https://outcomeschool.com/blog/how-ai-agents-communicate)

  </details>
- ✅ 🟢 `[Beginner]` What are Agent Skills?
  <details>
  <summary>💡 Answer</summary>

  [What are Agent Skills?](https://outcomeschool.com/blog/what-are-agent-skills)

  </details>
- ✅ 🟡 `[Intermediate]` How do you evaluate and test AI agents?
  <details>
  <summary>💡 Answer</summary>

  [AI Agent Evaluation](https://outcomeschool.com/blog/ai-agent-evaluation)

  </details>
- 🔲 🟢 `[Beginner]` What are the security risks of agentic systems, and how do you mitigate them?
- 🔲 🟢 `[Beginner]` What is the difference between reactive and proactive agents?
- 🔲 🟡 `[Intermediate]` How do you manage token consumption and cost in long-running agent workflows?
- 🔲 🟢 `[Beginner]` What is the human-in-the-loop pattern for agents, and when is it needed?
- 🔲 🟡 `[Intermediate]` How do you implement guardrails for AI agents to prevent harmful actions?
- ✅ 🟢 `[Beginner]` What is agent reflection, and how does it improve agent performance?
  <details>
  <summary>💡 Answer</summary>

  [Reflection Agent](https://outcomeschool.com/blog/reflection-agent)

  </details>
- 🔲 🟢 `[Beginner]` What is the difference between code-generating agents and tool-calling agents?
- 🔲 🟡 `[Intermediate]` How do you handle multi-modal inputs and outputs in agentic systems?
- ✅ 🟡 `[Intermediate]` How do you implement state management in complex agent workflows?
  <details>
  <summary>💡 Answer</summary>

  [How does LangGraph work?](https://outcomeschool.com/blog/how-does-langgraph-work)

  </details>
- 🔲 🟡 `[Intermediate]` How do you build a customer support agent with escalation logic?
- ✅ 🟢 `[Beginner]` What is agent orchestration, and how do you implement it?
  <details>
  <summary>💡 Answer</summary>

  [AI Orchestration](https://outcomeschool.com/blog/ai-orchestration)

  </details>
- 🔲 🟡 `[Intermediate]` How do you build a code execution agent safely using sandboxed environments?
- ✅ 🔴 `[Advanced]` Your AI agent is stuck in an infinite loop. How do you detect and break the cycle?
  <details>
  <summary>💡 Answer</summary>

  [Fix an infinite loop in an AI agent](https://www.linkedin.com/posts/pallavi-shekhar_ai-aiagents-machinelearning-share-7440257380707364864-5Ycc)

  </details>
- 🔲 🔴 `[Advanced]` Your AI agent gets conflicting answers from different tools. How does it reconcile them?
- ✅ 🔴 `[Advanced]` Your AI agent burns too many tokens per task. How do you reduce token consumption?
  <details>
  <summary>💡 Answer</summary>

  [How would you reduce the token consumption?](https://www.linkedin.com/posts/pallavi-shekhar_ai-aiagents-machinelearning-activity-7439550125015994368-LTmE)

  </details>
- 🔲 🔴 `[Advanced]` Your AI agent keeps exceeding its budget per task. How do you enforce budget limits?
- 🔲 🔴 `[Advanced]` Your AI agent hallucinates tool capabilities and passes wrong inputs. How do you fix it?
- 🔲 🔴 `[Advanced]` Your AI agent deleted a production database. How do you prevent irreversible actions?
- 🔲 🔴 `[Advanced]` Your AI agent has many tools, but keeps picking the wrong one. How do you improve tool selection?
- 🔲 🔴 `[Advanced]` Your AI agent takes too long to complete a task. How do you speed it up?
- 🔲 🔴 `[Advanced]` Your LLM selects the right tool but extracts the wrong parameters. How do you fix parameter extraction?
- ✅ 🟡 `[Intermediate]` How do Computer-Use Agents work?
  <details>
  <summary>💡 Answer</summary>

  [How do Computer-Use Agents work?](https://outcomeschool.com/blog/how-do-computer-use-agents-work)

  </details>
- ✅ 🟡 `[Intermediate]` How does LangChain work?
  <details>
  <summary>💡 Answer</summary>

  [How does LangChain work?](https://outcomeschool.com/blog/how-does-langchain-work)

  </details>
- ✅ 🟡 `[Intermediate]` How does LangGraph work?
  <details>
  <summary>💡 Answer</summary>

  [How does LangGraph work?](https://outcomeschool.com/blog/how-does-langgraph-work)

  </details>
- ✅ 🟢 `[Beginner]` What is OKF (Open Knowledge Format)?
  <details>
  <summary>💡 Answer</summary>

  [What is OKF (Open Knowledge Format)?](https://outcomeschool.com/blog/what-is-okf-open-knowledge-format) 

  </details>

### Fine-Tuning and Model Adaptation

- ✅ 🟢 `[Beginner]` What is fine-tuning, and when should you fine-tune an LLM?
  <details>
  <summary>💡 Answer</summary>

  Explained in this video: [AI Engineering Explained: LLM, RAG, MCP, Agent, Fine-Tuning, Quantization](https://www.youtube.com/watch?v=lnfWvX66FUk)

  </details>
- ✅ 🟡 `[Intermediate]` Explain the difference between full fine-tuning and parameter-efficient fine-tuning (PEFT).
  <details>
  <summary>💡 Answer</summary>

  Explained in this video: [AI Engineering Explained: LLM, RAG, MCP, Agent, Fine-Tuning, Quantization](https://www.youtube.com/watch?v=lnfWvX66FUk)

  </details>
- ✅ 🟢 `[Beginner]` What is LoRA (Low-Rank Adaptation), and how does it work?
  <details>
  <summary>💡 Answer</summary>

  Explained in this video: [AI Engineering Explained: LLM, RAG, MCP, Agent, Fine-Tuning, Quantization](https://www.youtube.com/watch?v=lnfWvX66FUk)

  </details>
- ✅ 🟢 `[Beginner]` What is QLoRA, and how does it enable fine-tuning on consumer hardware?
  <details>
  <summary>💡 Answer</summary>

  Explained in this video: [AI Engineering Explained: LLM, RAG, MCP, Agent, Fine-Tuning, Quantization](https://www.youtube.com/watch?v=lnfWvX66FUk)

  </details>
- ✅ 🟡 `[Intermediate]` How does fine-tuning work?
  <details>
  <summary>💡 Answer</summary>

  [How does fine-tuning work?](https://outcomeschool.com/blog/how-does-fine-tuning-work)

  </details>
- 🔲 🟡 `[Intermediate]` Explain Prefix Tuning and Prompt Tuning. How are they different from LoRA?
- ✅ 🟢 `[Beginner]` What is adapter-based fine-tuning?
  <details>
  <summary>💡 Answer</summary>

  Explained in this video: [AI Engineering Explained: LLM, RAG, MCP, Agent, Fine-Tuning, Quantization](https://www.youtube.com/watch?v=lnfWvX66FUk)

  </details>
- ✅ 🟡 `[Intermediate]` What is RLHF (Reinforcement Learning from Human Feedback), and how is it used to align LLMs?
  <details>
  <summary>💡 Answer</summary>

  [Reinforcement Learning from Human Feedback (RLHF)](https://outcomeschool.com/blog/reinforcement-learning-from-human-feedback-rlhf)

  </details>
- 🔲 🟢 `[Beginner]` What is instruction tuning, and why is it important for chat models?
- 🔲 🟡 `[Intermediate]` How do you prepare a dataset for fine-tuning an LLM?
- ✅ 🟢 `[Beginner]` What is catastrophic forgetting, and how do you prevent it during fine-tuning?
  <details>
  <summary>💡 Answer</summary>

  [Continual Learning in LLMs](https://outcomeschool.com/blog/continual-learning-in-llms)

  </details>
- 🔲 🟡 `[Intermediate]` When should you choose fine-tuning over RAG over prompt engineering?
- ✅ 🟡 `[Intermediate]` How do you evaluate a fine-tuned model's performance?
  <details>
  <summary>💡 Answer</summary>

  [LLM Evaluation](https://outcomeschool.com/blog/llm-evaluation)

  </details>
- 🔲 🟢 `[Beginner]` What is synthetic data generation, and how do you use it for fine-tuning?
- ✅ 🟢 `[Beginner]` What are the key hyperparameters for fine-tuning (learning rate, epochs, batch size, LoRA rank)?
  <details>
  <summary>💡 Answer</summary>

  [LoRA - Low-Rank Adaptation of LLMs](https://outcomeschool.com/blog/lora-low-rank-adaptation-of-llms)

  </details>
- 🔲 🟡 `[Intermediate]` How do you fine-tune a model for a specific domain (legal, medical, finance)?
- 🔲 🟢 `[Beginner]` What is continual pre-training, and when would you use it?
- ✅ 🟡 `[Intermediate]` How do you merge multiple LoRA adapters?
  <details>
  <summary>💡 Answer</summary>

  [LoRA - Low-Rank Adaptation of LLMs](https://outcomeschool.com/blog/lora-low-rank-adaptation-of-llms)

  </details>
- 🔲 🟢 `[Beginner]` What is the difference between SFT (Supervised Fine-Tuning) and alignment training?
- 🔲 🟡 `[Intermediate]` What is RLAIF (RL from AI Feedback), and how does it differ from RLHF?
- ✅ 🟢 `[Beginner]` What is knowledge distillation for fine-tuning, and what are the legal considerations?
  <details>
  <summary>💡 Answer</summary>

  [How does Knowledge Distillation work?](https://outcomeschool.com/blog/how-does-knowledge-distillation-work)

  </details>
- 🔲 🔴 `[Advanced]` Your fine-tuned LLM produces factually wrong outputs due to training data quality issues. How do you fix it?
- ✅ 🟡 `[Intermediate]` You must choose between LoRA and full fine-tuning for a domain-specific assistant. How do you decide?
  <details>
  <summary>💡 Answer</summary>

  [LoRA - Low-Rank Adaptation of LLMs](https://outcomeschool.com/blog/lora-low-rank-adaptation-of-llms)

  </details>
- 🔲 🔴 `[Advanced]` Your fine-tuned model memorized training data verbatim instead of learning patterns. How do you fix overfitting?
- ✅ 🔴 `[Advanced]` Your fine-tuned LLM forgot its general capabilities after domain-specific fine-tuning. How do you fix catastrophic forgetting?
  <details>
  <summary>💡 Answer</summary>

  [Continual Learning in LLMs](https://outcomeschool.com/blog/continual-learning-in-llms)

  </details>
- 🔲 🔴 `[Advanced]` Your RLHF preference data has low annotator agreement. How do you ensure data quality?

### Vector Databases and Embeddings

- ✅ 🟢 `[Beginner]` What are embeddings in the context of AI engineering?
  <details>
  <summary>💡 Answer</summary>

  [Embeddings in Machine Learning](https://www.youtube.com/watch?v=LedXW6xl21s)

  </details>
- ✅ 🟢 `[Beginner]` How do embedding models convert text to vectors?
  <details>
  <summary>💡 Answer</summary>

  [What are Embeddings?](https://outcomeschool.com/blog/what-are-embeddings)

  </details>
- 🔲 🟢 `[Beginner]` What is the difference between sparse and dense embeddings?
- ✅ 🟡 `[Intermediate]` Explain cosine similarity, dot product, and Euclidean distance for vector search.
  <details>
  <summary>💡 Answer</summary>

  [How does a Vector Database work?](https://outcomeschool.com/blog/how-does-a-vector-database-work)

  </details>
- ✅ 🟢 `[Beginner]` What is a vector database, and how does it differ from a traditional database?
  <details>
  <summary>💡 Answer</summary>

  [How does a Vector Database work?](https://outcomeschool.com/blog/how-does-a-vector-database-work)

  </details>
- ✅ 🟡 `[Intermediate]` How does Approximate Nearest Neighbor (ANN) search work?
  <details>
  <summary>💡 Answer</summary>

  [How does Approximate Nearest Neighbor (ANN) search work?](https://outcomeschool.com/blog/how-does-approximate-nearest-neighbor-ann-search-work)

  </details>
- 🔲 🟡 `[Intermediate]` How do you choose the right embedding model for your use case?
- 🔲 🟢 `[Beginner]` What is embedding dimensionality, and how does it affect performance and cost?
- 🔲 🟡 `[Intermediate]` How do you handle embedding drift when the embedding model is updated?
- ✅ 🟢 `[Beginner]` What are multi-modal embeddings, and how are they generated?
  <details>
  <summary>💡 Answer</summary>

  [Multimodal AI](https://outcomeschool.com/blog/multimodal-ai)

  </details>
- 🔲 🟡 `[Intermediate]` How do you index and query multi-tenant data in a vector database?
- 🔲 🟢 `[Beginner]` What is quantization of embeddings, and how does it reduce storage costs?
- 🔲 🟡 `[Intermediate]` How do you benchmark and evaluate embedding model quality?
- ✅ 🟢 `[Beginner]` What is the role of metadata in vector databases?
  <details>
  <summary>💡 Answer</summary>

  [How does a Vector Database work?](https://outcomeschool.com/blog/how-does-a-vector-database-work)

  </details>
- ✅ 🔴 `[Advanced]` How do you handle large-scale vector search with billions of vectors?
  <details>
  <summary>💡 Answer</summary>

  [How does Approximate Nearest Neighbor (ANN) search work?](https://outcomeschool.com/blog/how-does-approximate-nearest-neighbor-ann-search-work)

  </details>
- ✅ 🟢 `[Beginner]` What is hybrid search (combining keyword search with vector search)?
  <details>
  <summary>💡 Answer</summary>

  [How does Hybrid Search work?](https://outcomeschool.com/blog/how-does-hybrid-search-work) 

  </details>
- 🔲 🟡 `[Intermediate]` How do you fine-tune an embedding model for a specific domain?
- 🔲 🔴 `[Advanced]` Your vector database for RAG is consuming too much memory. How do you reduce it?
- 🔲 🔴 `[Advanced]` Your vector database cannot scale to millions of embeddings. How do you fix the bottleneck?
- 🔲 🔴 `[Advanced]` Your new embedding model has different dimensions from the existing vectors in production. How do you handle the mismatch?
- 🔲 🔴 `[Advanced]` Your vector search returns irrelevant results despite high similarity scores. How do you fix it?
- 🔲 🟡 `[Intermediate]` You deployed a new embedding model, and search quality crashed overnight. How do you handle embedding drift?
- 🔲 🔴 `[Advanced]` Your semantic search fails for short queries. How do you improve it?

### AI System Design

- 🔲 🔴 `[Advanced]` Design ChatGPT: Training to Serving (End to End)
- 🔲 🔴 `[Advanced]` Design a RAG System (Chat with Your Documents)
- ✅ 🔴 `[Advanced]` Design Memory for a Personal AI Assistant
  <details>
  <summary>💡 Answer</summary>

  [AI Agent Memory](https://outcomeschool.com/blog/ai-agent-memory)

  </details>
- 🔲 🔴 `[Advanced]` Design a Deep Research Agent
- ✅ 🔴 `[Advanced]` Design a Multi-Agent Customer Support System
  <details>
  <summary>💡 Answer</summary>

  [Multi-Agent Systems](https://outcomeschool.com/blog/multi-agent-systems)

  </details>
- 🔲 🔴 `[Advanced]` Design an On-Device AI Assistant
- 🔲 🔴 `[Advanced]` Design a Multimodal Search System (Text, Image, Video)
- ✅ 🔴 `[Advanced]` Design an LLM Inference Platform (vLLM-as-a-Service)
  <details>
  <summary>💡 Answer</summary>

  [How does vLLM work?](https://outcomeschool.com/blog/how-does-vllm-work) and [LLM Inference Optimization](https://outcomeschool.com/blog/llm-inference-optimization)

  </details>
- ✅ 🔴 `[Advanced]` Design an LLM Evaluation Platform
  <details>
  <summary>💡 Answer</summary>

  [LLM Evaluation](https://outcomeschool.com/blog/llm-evaluation)

  </details>
- 🔲 🔴 `[Advanced]` Design a Text-to-Image Generation Service (Midjourney-like)
- 🔲 🔴 `[Advanced]` Design a Music Generation Service (Suno-like)
- 🔲 🔴 `[Advanced]` Design a Video Generation Service (Sora-like)
- ✅ 🔴 `[Advanced]` Design an AI Coding Agent.
  <details>
  <summary>💡 Answer</summary>

  [How does Claude Code work?](https://outcomeschool.com/blog/how-does-claude-code-work) and [How does Cursor work?](https://outcomeschool.com/blog/how-does-cursor-work)

  </details>
- 🔲 🔴 `[Advanced]` Design a code generation and review system.
- 🔲 🔴 `[Advanced]` Design a content moderation system using AI.
- 🔲 🔴 `[Advanced]` Design a real-time AI recommendation system.
- 🔲 🔴 `[Advanced]` Design an AI-powered email assistant.
- 🔲 🔴 `[Advanced]` Design a medical diagnosis assistant using AI.
- 🔲 🔴 `[Advanced]` Design a fraud detection system powered by LLMs.
- 🔲 🔴 `[Advanced]` Design an AI-powered data extraction pipeline from unstructured documents.
- 🔲 🔴 `[Advanced]` Design a personalized learning assistant.
- 🔲 🔴 `[Advanced]` Design an AI system for automated code migration.
- 🔲 🔴 `[Advanced]` Design an AI-powered legal document review system.
- ✅ 🔴 `[Advanced]` Design a conversational AI system with memory across sessions.
  <details>
  <summary>💡 Answer</summary>

  [AI Agent Memory](https://outcomeschool.com/blog/ai-agent-memory)

  </details>
- 🔲 🔴 `[Advanced]` How do you design for latency vs quality trade-offs in AI systems?
- 🔲 🔴 `[Advanced]` How do you implement caching strategies for LLM applications?
- 🔲 🔴 `[Advanced]` How do you design rate limiting and cost management for AI APIs?
- 🔲 🔴 `[Advanced]` How do you handle failover and fallback strategies for AI systems?
- 🔲 🔴 `[Advanced]` How do you design an AI system for high availability and fault tolerance?
- 🔲 🔴 `[Advanced]` How do you design an AI system that gracefully degrades when the model is unavailable?
- 🔲 🔴 `[Advanced]` What are the key considerations for multi-region deployment of AI systems?
- 🔲 🔴 `[Advanced]` Design an AI-powered search engine for an e-commerce platform.
- 🔲 🔴 `[Advanced]` Design an AI gateway/proxy for managing LLM access across an organization.
- 🔲 🔴 `[Advanced]` How do you design a RAG system that handles conflicting information across sources?
- 🔲 🔴 `[Advanced]` How do you approach capacity planning for an AI system?
- 🔲 🔴 `[Advanced]` Design a multi-tenant AI chatbot platform where each business gets a custom chatbot.
- 🔲 🔴 `[Advanced]` Design an AI meeting summarizer system for thousands of meetings daily.
- 🔲 🔴 `[Advanced]` Design an AI notification system that prioritizes instead of broadcasting.
- 🔲 🔴 `[Advanced]` Design an AI-powered anomaly detection system for cloud infrastructure.
- 🔲 🔴 `[Advanced]` Design an AI-powered document processing pipeline for financial institutions.
- 🔲 🔴 `[Advanced]` Design an AI dynamic pricing engine.
- 🔲 🔴 `[Advanced]` Design an AI resume screening system that handles 100K applications per week.
- 🔲 🔴 `[Advanced]` Design an AI voice assistant architecture.
- ✅ 🔴 `[Advanced]` Design a multi-agent workflow system where agents collaborate on complex tasks.
  <details>
  <summary>💡 Answer</summary>

  [Multi-Agent Systems](https://outcomeschool.com/blog/multi-agent-systems)

  </details>
- 🔲 🔴 `[Advanced]` Design a real-time AI transcription system for concurrent audio streams.
- 🔲 🔴 `[Advanced]` Design an AI-powered live streaming content moderation system.

### LLMOps and Production AI

- ✅ 🟡 `[Intermediate]` How does Prompt Caching work?
  <details>
  <summary>💡 Answer</summary>

  [How does Prompt Caching work?](https://outcomeschool.com/blog/how-does-prompt-caching-work)

  </details>
- ✅ 🟡 `[Intermediate]` Prefill vs Decode
  <details>
  <summary>💡 Answer</summary>

  [Prefill vs Decode: LLM Inference Optimization](https://outcomeschool.com/blog/prefill-vs-decode-llm-inference-optimization)

  </details>
- 🔲 🔴 `[Advanced]` Explain the AI product lifecycle from ideation to production.
- 🔲 🟢 `[Beginner]` What is LLMOps, and how does it differ from traditional MLOps?
- 🔲 🔴 `[Advanced]` How do you serve LLMs in production?
- ✅ 🟢 `[Beginner]` What is model quantization?
  <details>
  <summary>💡 Answer</summary>

  Explained in this video: [AI Engineering Explained: LLM, RAG, MCP, Agent, Fine-Tuning, Quantization](https://www.youtube.com/watch?v=lnfWvX66FUk)

  </details>
- ✅ 🔴 `[Advanced]` How do you monitor LLM applications in production?
  <details>
  <summary>💡 Answer</summary>

  [AI Agent Observability](https://outcomeschool.com/blog/ai-agent-observability)

  </details>
- ✅ 🟢 `[Beginner]` What is LLM observability?
  <details>
  <summary>💡 Answer</summary>

  [AI Agent Observability](https://outcomeschool.com/blog/ai-agent-observability)

  </details>
- 🔲 🟢 `[Beginner]` What are guardrails for LLMs, and how do you implement them?
- 🔲 🟡 `[Intermediate]` How do you implement content filtering for AI outputs?
- 🔲 🔴 `[Advanced]` How do you estimate the cost of running an AI-powered feature in production?
- ✅ 🔴 `[Advanced]` How do you optimize LLM inference costs in production?
  <details>
  <summary>💡 Answer</summary>

  [LLM Inference Optimization](https://outcomeschool.com/blog/llm-inference-optimization)

  </details>
- 🔲 🟡 `[Intermediate]` How do you implement A/B testing for LLM systems?
- 🔲 🟢 `[Beginner]` What is CI/CD for AI applications, and how does it differ from traditional CI/CD?
- 🔲 🔴 `[Advanced]` How do you version and manage prompts in production?
- 🔲 🟢 `[Beginner]` What is model versioning, and how do you handle model rollbacks?
- 🔲 🔴 `[Advanced]` How do you implement rate limiting and throttling for LLM APIs?
- 🔲 🟡 `[Intermediate]` How do you handle model updates and migrations without downtime?
- 🔲 🟢 `[Beginner]` What is the role of feature flags in AI deployments?
- ✅ 🟡 `[Intermediate]` How do you implement logging and tracing for LLM applications?
  <details>
  <summary>💡 Answer</summary>

  [AI Agent Observability](https://outcomeschool.com/blog/ai-agent-observability)

  </details>
- 🔲 🟡 `[Intermediate]` How do you handle PII and sensitive data in LLM inputs and outputs?
- 🔲 🟢 `[Beginner]` What is a gateway pattern for LLM API management?
- ✅ 🟡 `[Intermediate]` How does Token Streaming work?
  <details>
  <summary>💡 Answer</summary>

  [How does Token Streaming work?](https://outcomeschool.com/blog/how-does-token-streaming-work)

  </details>
- ✅ 🟡 `[Intermediate]` How do you implement streaming responses for real-time AI applications?
  <details>
  <summary>💡 Answer</summary>

  [How does Token Streaming work?](https://outcomeschool.com/blog/how-does-token-streaming-work)

  </details>
- ✅ 🟡 `[Intermediate]` How does vLLM work?
  <details>
  <summary>💡 Answer</summary>

  [How does vLLM work?](https://outcomeschool.com/blog/how-does-vllm-work)

  </details>
- ✅ 🟡 `[Intermediate]` How does SGLang work?
  <details>
  <summary>💡 Answer</summary>

  [How does SGLang work?](https://outcomeschool.com/blog/how-does-sglang-work)

  </details>
- 🔲 🔴 `[Advanced]` What are the key SLAs and metrics for production AI systems (latency, throughput, availability)?
- ✅ 🟡 `[Intermediate]` Cloud vs on-device Model Deployment for AI applications.
  <details>
  <summary>💡 Answer</summary>

  [Cloud vs On-Device Model Deployment](https://x.com/outcome_school/status/1965643330076991621)

  </details>
- 🔲 🟡 `[Intermediate]` How do you implement fallback strategies when the primary model is unavailable or rate-limited?
- 🔲 🔴 `[Advanced]` How do you implement structured output from LLMs reliably in production?
- 🔲 🔴 `[Advanced]` How do you handle long contexts efficiently in production (context compression, prefix caching)?
- ✅ 🟢 `[Beginner]` What is semantic routing, and how do you implement it in a multi-model system?
  <details>
  <summary>💡 Answer</summary>

  [LLM Routing](https://outcomeschool.com/blog/llm-routing)

  </details>
- 🔲 🟡 `[Intermediate]` How do you manage secrets and API keys securely in LLM applications?
- 🔲 🔴 `[Advanced]` Your LLM API has latency spikes during peak hours. How do you stabilize it?
- 🔲 🔴 `[Advanced]` Your LLM costs are too high in production. How do you reduce costs without degrading quality?
- 🔲 🔴 `[Advanced]` Your application is hitting LLM provider rate limits during peak hours. How do you handle it?
- 🔲 🔴 `[Advanced]` Your application depends on one LLM provider. How do you switch providers without downtime?
- 🔲 🔴 `[Advanced]` Your AI system handles 100 requests/sec but crashes at 5000. How do you scale for concurrent requests?
- 🔲 🔴 `[Advanced]` A traffic spike brings down your AI system. How do you handle peak traffic?
- 🔲 🔴 `[Advanced]` One LLM provider outage took down your entire system. How do you eliminate single points of failure?
- ✅ 🔴 `[Advanced]` Your multi-LLM pipeline fails when one model in the chain breaks. How do you handle orchestration failure?
  <details>
  <summary>💡 Answer</summary>

  [AI Orchestration](https://outcomeschool.com/blog/ai-orchestration)

  </details>
- ✅ 🔴 `[Advanced]` Your AI pipeline has zero visibility into which step is failing. How do you add observability?
  <details>
  <summary>💡 Answer</summary>

  [AI Agent Observability](https://outcomeschool.com/blog/ai-agent-observability)

  </details>
- 🔲 🟡 `[Intermediate]` You quantized your LLM, but accuracy dropped significantly. How do you minimize quantization loss?
- 🔲 🟡 `[Intermediate]` One failing AI component can take down your entire platform. How do you design graceful degradation?

### Evaluation and Testing

- ✅ 🟡 `[Intermediate]` AI Agent Evaluation
  <details>
  <summary>💡 Answer</summary>

  [AI Agent Evaluation](https://outcomeschool.com/blog/ai-agent-evaluation)

  </details>
- ✅ 🟡 `[Intermediate]` LLM Evaluation
  <details>
  <summary>💡 Answer</summary>

  [LLM Evaluation](https://outcomeschool.com/blog/llm-evaluation)

  </details>
- ✅ 🟡 `[Intermediate]` AI Agent Observability
  <details>
  <summary>💡 Answer</summary>

  [AI Agent Observability](https://outcomeschool.com/blog/ai-agent-observability)

  </details>
- 🔲 🟢 `[Beginner]` What is evaluation-driven development for AI applications?
- ✅ 🟡 `[Intermediate]` How do you evaluate LLM outputs? What metrics do you use?
  <details>
  <summary>💡 Answer</summary>

  [LLM Evaluation](https://outcomeschool.com/blog/llm-evaluation)

  </details>
- ✅ 🟡 `[Intermediate]` Explain BLEU, ROUGE, and BERTScore. When would you use each?
  <details>
  <summary>💡 Answer</summary>

  [LLM Evaluation](https://outcomeschool.com/blog/llm-evaluation)

  </details>
- ✅ 🟢 `[Beginner]` What is G-Eval, and how does it use LLMs for evaluation?
  <details>
  <summary>💡 Answer</summary>

  [LLM as a Judge](https://outcomeschool.com/blog/llm-as-a-judge)

  </details>
- ✅ 🟢 `[Beginner]` What is LLM-as-a-judge evaluation, and what are its limitations?
  <details>
  <summary>💡 Answer</summary>

  [LLM as a Judge](https://outcomeschool.com/blog/llm-as-a-judge)

  </details>
- 🔲 🟡 `[Intermediate]` How do you conduct human evaluation for AI systems?
- 🔲 🔴 `[Advanced]` What is red teaming, and how do you red team an LLM application?
- 🔲 🟡 `[Intermediate]` How do you detect and measure hallucinations in LLM outputs?
- 🔲 🟢 `[Beginner]` What is adversarial testing for AI systems?
- 🔲 🟡 `[Intermediate]` How do you build a regression test suite for AI applications?
- ✅ 🟢 `[Beginner]` What are benchmark suites (MMLU, HumanEval, GSM8K), and how do you interpret them?
  <details>
  <summary>💡 Answer</summary>

  [LLM Evaluation](https://outcomeschool.com/blog/llm-evaluation)

  </details>
- 🔲 🟡 `[Intermediate]` How do you evaluate a RAG system end-to-end?
- ✅ 🟡 `[Intermediate]` How do you evaluate the quality of AI agents?
  <details>
  <summary>💡 Answer</summary>

  [AI Agent Evaluation](https://outcomeschool.com/blog/ai-agent-evaluation)

  </details>
- 🔲 🟢 `[Beginner]` What is the difference between offline and online evaluation for AI systems?
- 🔲 🟡 `[Intermediate]` How do you measure factual consistency in LLM outputs?
- 🔲 🟡 `[Intermediate]` How do you evaluate multi-turn conversation quality?
- 🔲 🟢 `[Beginner]` What is the role of golden datasets in AI evaluation?
- 🔲 🔴 `[Advanced]` How do you implement continuous evaluation for production AI systems?
- 🔲 🟡 `[Intermediate]` How do you evaluate bias in AI model outputs?
- 🔲 🟡 `[Intermediate]` How do you compare two models or prompts in a statistically rigorous way?
- 🔲 🟡 `[Intermediate]` How do you evaluate the robustness of an LLM application across input variations?
- 🔲 🟢 `[Beginner]` What are the key differences between evaluating traditional ML vs LLM applications?
- ✅ 🟡 `[Intermediate]` How do you set up an evaluation framework from scratch for a new LLM application?
  <details>
  <summary>💡 Answer</summary>

  [LLM Evaluation](https://outcomeschool.com/blog/llm-evaluation)

  </details>
- 🔲 🔴 `[Advanced]` Your model passes one fairness metric but fails another. How do you handle conflicting audit results?
- 🔲 🔴 `[Advanced]` Your model was fair at deployment, but became biased 6 months later. How do you monitor continuously?
- 🔲 🟡 `[Intermediate]` An external auditor cannot reproduce your model's results. How do you ensure audit reproducibility?
- 🔲 🔴 `[Advanced]` How do you structure red teaming for an LLM chatbot before launch?
- 🔲 🔴 `[Advanced]` How do you red team a multimodal model where text-only safety tests miss cross-modal attacks?

### AI Safety, Ethics, and Responsible AI

- 🔲 🟢 `[Beginner]` What are hallucinations in LLMs, and how do you mitigate them?
- 🔲 🟢 `[Beginner]` What is prompt injection, and what are the different types (direct, indirect)?
- 🔲 🟡 `[Intermediate]` How do you implement input and output guardrails for AI systems?
- 🔲 🟢 `[Beginner]` What is AI alignment, and why is it important?
- 🔲 🟡 `[Intermediate]` How do you detect and mitigate bias in AI systems?
- 🔲 🔴 `[Advanced]` What are the key data privacy considerations (GDPR, CCPA) when building AI applications?
- 🔲 🟡 `[Intermediate]` How do you handle PII in LLM inputs and outputs?
- 🔲 🟢 `[Beginner]` What is explainability in AI, and why does it matter?
- 🔲 🟢 `[Beginner]` What is the difference between interpretability and explainability?
- 🔲 🟡 `[Intermediate]` How do you build trust with users in AI-powered applications?
- 🔲 🟢 `[Beginner]` What are adversarial attacks on AI systems, and how do you defend against them?
- 🔲 🔴 `[Advanced]` What is data poisoning, and how can it affect AI models?
- 🔲 🟡 `[Intermediate]` How do you implement content safety filters for AI-generated content?
- 🔲 🟢 `[Beginner]` What is responsible AI, and what frameworks exist for implementing it?
- 🔲 🟡 `[Intermediate]` How do you handle copyright and intellectual property concerns with AI-generated content?
- 🔲 🟢 `[Beginner]` What is the EU AI Act, and how does it affect AI engineering?
- 🔲 🔴 `[Advanced]` How do you implement audit trails and logging for AI decisions?
- 🔲 🟢 `[Beginner]` What is model card documentation, and why is it important?
- 🔲 🔴 `[Advanced]` How do you handle misuse and abuse of AI systems in production?
- 🔲 🟢 `[Beginner]` What is differential privacy, and how can it be applied during model training?
- 🔲 🔴 `[Advanced]` How would you design an AI incident response plan?
- 🔲 🟢 `[Beginner]` What is the NIST AI Risk Management Framework (AI RMF)?
- 🔲 🔴 `[Advanced]` Your healthcare chatbot gives medical diagnoses it should not make. How do you add safety guardrails?
- 🔲 🔴 `[Advanced]` Your AI system is reproducing copyrighted material verbatim. How do you prevent this?
- 🔲 🔴 `[Advanced]` Your resume screening AI rejects more female candidates for engineering roles. How do you fix gender bias?
- 🔲 🔴 `[Advanced]` Your AI model passes bias checks by gender and race separately, but fails for intersectional groups. How do you handle it?
- 🔲 🔴 `[Advanced]` Your AI denied a loan, and the customer demands a GDPR explanation. How do you provide one?
- 🔲 🔴 `[Advanced]` A user invokes the right to be forgotten, but their data is in your model weights. How do you comply?
- 🔲 🟡 `[Intermediate]` The EU AI Act may classify your AI system as high-risk. How do you comply?
- 🔲 🔴 `[Advanced]` Your differentially private model lost significant accuracy. How do you balance privacy and utility?
- 🔲 🔴 `[Advanced]` One malicious participant is poisoning your federated learning model. How do you defend against it?
- 🔲 🔴 `[Advanced]` Your AI hiring model uses proxy features for protected attributes. How do you eliminate proxy discrimination?
- 🔲 🔴 `[Advanced]` Your predictive model creates a feedback loop of biased outcomes. How do you break it?
- 🔲 🔴 `[Advanced]` Your AI generates fake news images. How do you implement watermarking for AI-generated content?
- 🔲 🔴 `[Advanced]` Your AI denies a service, and the user has no way to challenge it. How do you design an appeals process?
- 🔲 🔴 `[Advanced]` An auditor asks why your AI rejected a request 6 months ago, and you have no logs. How do you build audit trails?
- 🔲 🟡 `[Intermediate]` You removed PII, but users were re-identified from anonymized data. How do you prevent re-identification?
- 🔲 🟡 `[Intermediate]` A pre-trained model from an open-source repo may contain a hidden backdoor. How do you detect it?
- 🔲 🔴 `[Advanced]` Your LLM's training data was deliberately poisoned by an adversary. How do you respond?
- 🔲 🔴 `[Advanced]` Your AI mental health chatbot gave harmful advice to a user in crisis. How do you mitigate harm?
- 🔲 🔴 `[Advanced]` Your AI system caused incorrect critical decisions. How do you run a blameless post-mortem?
- 🔲 🟡 `[Intermediate]` Radiologists agree with AI 98% of the time, even when it is wrong. How do you prevent human over-reliance on AI?
- 🔲 🔴 `[Advanced]` Your content moderation flags normal cultural expressions as offensive in other markets. How do you adapt cross-culturally?
- 🔲 🔴 `[Advanced]` Your AI training produces massive carbon emissions. How do you reduce environmental impact?

### Multimodal AI

- ✅ 🟢 `[Beginner]` What are Multimodal AI models, and how do they process different types of data?
  <details>
  <summary>💡 Answer</summary>

  [Multimodal AI](https://outcomeschool.com/blog/multimodal-ai)

  </details>
- ✅ 🟡 `[Intermediate]` How do vision-language models process images?
  <details>
  <summary>💡 Answer</summary>

  [Multimodal AI](https://outcomeschool.com/blog/multimodal-ai)

  </details>
- 🔲 🟡 `[Intermediate]` How does CLIP work, and why is it important for multi-modal AI?
- 🔲 🟢 `[Beginner]` What are the key architectures for multi-modal models?
- ✅ 🟡 `[Intermediate]` How does image generation work with diffusion models (Stable Diffusion, DALL-E, Flux)?
  <details>
  <summary>💡 Answer</summary>

  [Diffusion Models](https://outcomeschool.com/blog/diffusion-models)

  </details>
- 🔲 🟢 `[Beginner]` What is text-to-speech (TTS), and what models are used for it?
- 🔲 🟡 `[Intermediate]` How does speech-to-text (Whisper) work?
- 🔲 🟢 `[Beginner]` What is multi-modal RAG, and how does it differ from text-only RAG?
- 🔲 🟡 `[Intermediate]` How do you build a system that processes both images and text?
- ✅ 🟢 `[Beginner]` What are multi-modal embeddings, and how are they used for cross-modal search?
  <details>
  <summary>💡 Answer</summary>

  [Multimodal AI](https://outcomeschool.com/blog/multimodal-ai)

  </details>
- 🔲 🟡 `[Intermediate]` How do you evaluate multi-modal AI systems?
- 🔲 🟢 `[Beginner]` What are the challenges of real-time multi-modal AI processing?
- 🔲 🟡 `[Intermediate]` How do you handle video understanding with AI?
- 🔲 🟢 `[Beginner]` What is visual question answering (VQA)?
- 🔲 🟢 `[Beginner]` What is document understanding, and how do models parse documents with layouts?
- 🔲 🟡 `[Intermediate]` How do you fine-tune a vision-language model?
- 🔲 🔴 `[Advanced]` What are the latency and cost considerations for multi-modal AI in production?
- 🔲 🟡 `[Intermediate]` How do you handle multi-modal content moderation?
- 🔲 🟢 `[Beginner]` What is text-to-video generation, and what are the current state-of-the-art approaches?
- 🔲 🟡 `[Intermediate]` Explain Multimodal Fusion Techniques: Early Fusion vs Late Fusion.
- 🔲 🔴 `[Advanced]` Your vision-language model generates factually incorrect image descriptions. How do you fix it?
- 🔲 🔴 `[Advanced]` Your VLM answers single-image questions but fails on multi-page documents. How do you fix it?
- 🔲 🔴 `[Advanced]` Your multimodal LLM ignores the image and generates descriptions from text alone. How do you fix it?
- 🔲 🔴 `[Advanced]` Your diffusion model ignores precise control requirements in text prompts. How do you improve controllability?
- 🔲 🔴 `[Advanced]` Your diffusion model generates sharp but repetitive images. How do you balance quality vs diversity?
- 🔲 🔴 `[Advanced]` Your diffusion model takes too long per image. How do you speed up sampling?

### AI Infrastructure and Scalability

- ✅ 🔴 `[Advanced]` How do you improve inference speed in production LLM deployments?
  <details>
  <summary>💡 Answer</summary>

  [LLM Inference Optimization](https://www.youtube.com/watch?v=jV2sCj4lHYk)

  </details>
- ✅ 🔴 `[Advanced]` LLM optimization techniques
  <details>
  <summary>💡 Answer</summary>

  [LLM optimization techniques](https://www.linkedin.com/posts/pallavi-shekhar_5-llm-optimization-techniques-lets-understand-activity-7442067281532325888-4aOS)

  </details>
- 🔲 🔴 `[Advanced]` How do you select GPUs for LLM inference?
- 🔲 🔴 `[Advanced]` What is model parallelism vs data parallelism in distributed training?
- 🔲 🔴 `[Advanced]` What is tensor parallelism, and how does it help serve large models?
- 🔲 🔴 `[Advanced]` What is pipeline parallelism?
- ✅ 🔴 `[Advanced]` How does continuous batching improve LLM inference throughput?
  <details>
  <summary>💡 Answer</summary>

  [Continuous Batching in LLMs](https://outcomeschool.com/blog/continuous-batching-in-llms)

  </details>
- ✅ 🔴 `[Advanced]` What is speculative decoding, and how does it speed up inference?
  <details>
  <summary>💡 Answer</summary>

  [Speculative Decoding](https://outcomeschool.com/blog/speculative-decoding)

  </details>
- ✅ 🔴 `[Advanced]` What is KV cache, and how do you manage memory for it?
  <details>
  <summary>💡 Answer</summary>

  [What is KV Cache in LLMs?](https://outcomeschool.com/blog/kv-cache-in-llms)

  </details>
- ✅ 🔴 `[Advanced]` What is Paged Attention?
  <details>
  <summary>💡 Answer</summary>

  [Paged Attention in LLMs](https://outcomeschool.com/blog/paged-attention-in-llms)

  </details>
- ✅ 🔴 `[Advanced]` How does GGUF work?
  <details>
  <summary>💡 Answer</summary>

  [How does GGUF work?](https://outcomeschool.com/blog/how-does-gguf-work)

  </details>
- 🔲 🔴 `[Advanced]` How do you optimize inference for edge and mobile deployment?
- ✅ 🔴 `[Advanced]` What is model quantization (INT8, INT4, FP16, BF16), and how does it affect quality?
  <details>
  <summary>💡 Answer</summary>

  Explained in this video: [AI Engineering Explained: LLM, RAG, MCP, Agent, Fine-Tuning, Quantization](https://www.youtube.com/watch?v=lnfWvX66FUk)

  </details>
- 🔲 🔴 `[Advanced]` How do you implement auto-scaling for AI workloads?
- 🔲 🔴 `[Advanced]` What is the role of load balancing in AI serving infrastructure?
- 🔲 🔴 `[Advanced]` How do you manage GPU memory for serving multiple models?
- 🔲 🔴 `[Advanced]` What is model sharding, and when would you use it?
- 🔲 🔴 `[Advanced]` How do you implement request queuing and priority scheduling for AI services?
- 🔲 🔴 `[Advanced]` What are the cost trade-offs between self-hosted and API-based AI inference?
- 🔲 🔴 `[Advanced]` How do you handle cold start latency for serverless AI deployments?
- 🔲 🔴 `[Advanced]` How do you implement model caching to reduce redundant computations?
- 🔲 🔴 `[Advanced]` What is the difference between synchronous and asynchronous inference, and when do you use each?
- 🔲 🔴 `[Advanced]` What is FSDP (Fully Sharded Data Parallel), and how does it differ from DeepSpeed ZeRO?
- 🔲 🔴 `[Advanced]` How do you monitor and profile LLM inference in production (TTFT, inter-token latency, GPU utilization)?
- ✅ 🔴 `[Advanced]` What is model routing at the infrastructure level, and how do you route requests based on complexity and cost?
  <details>
  <summary>💡 Answer</summary>

  [LLM Routing](https://outcomeschool.com/blog/llm-routing)

  </details>

### Coding and Practical Implementation

- 🔲 🟡 `[Intermediate]` Implement a basic RAG pipeline using an embedding model and a vector database.
- ✅ 🟡 `[Intermediate]` Build a simple AI agent with tool use (e.g., calculator, web search).
  <details>
  <summary>💡 Answer</summary>

  [ReAct Agent](https://outcomeschool.com/blog/react-agent)

  </details>
- ✅ 🟡 `[Intermediate]` Implement semantic search using embeddings and cosine similarity.
  <details>
  <summary>💡 Answer</summary>

  [How does Semantic Search work?](https://outcomeschool.com/blog/how-does-semantic-search-work) and [How does a Vector Database work?](https://outcomeschool.com/blog/how-does-a-vector-database-work)

  </details>
- 🔲 🟡 `[Intermediate]` Write code for different text chunking strategies (fixed-size, recursive, semantic).
- 🔲 🟡 `[Intermediate]` Implement a prompt template system with variable substitution.
- ✅ 🟡 `[Intermediate]` Build an evaluation pipeline for LLM outputs using LLM-as-a-judge.
  <details>
  <summary>💡 Answer</summary>

  [LLM as a Judge](https://outcomeschool.com/blog/llm-as-a-judge)

  </details>
- ✅ 🟡 `[Intermediate]` Implement streaming responses for an LLM API.
  <details>
  <summary>💡 Answer</summary>

  [How does Token Streaming work?](https://outcomeschool.com/blog/how-does-token-streaming-work)

  </details>
- 🔲 🟡 `[Intermediate]` Build a simple vector similarity search from scratch.
- 🔲 🟡 `[Intermediate]` Implement a conversation memory system for a chatbot (sliding window, summary, buffer).
- 🔲 🟡 `[Intermediate]` Write code to detect and handle hallucinations in LLM outputs.
- 🔲 🟡 `[Intermediate]` Implement a retry mechanism with exponential backoff for LLM API calls.
- ✅ 🟡 `[Intermediate]` Write a function calling (tool use) handler for an LLM API.
  <details>
  <summary>💡 Answer</summary>

  [How does Function Calling work in LLMs?](https://outcomeschool.com/blog/how-does-function-calling-work-in-llms)

  </details>
- ✅ 🟡 `[Intermediate]` Implement a simple re-ranker for search results.
  <details>
  <summary>💡 Answer</summary>

  [How does a Reranker work?](https://outcomeschool.com/blog/how-does-a-reranker-work)

  </details>
- 🔲 🟡 `[Intermediate]` Build a basic document parser that extracts text from PDFs and splits it into chunks.
- 🔲 🟡 `[Intermediate]` Implement cosine similarity, dot product, and Euclidean distance functions from scratch.
- 🔲 🟡 `[Intermediate]` Write code to implement token counting and context window management.
- 🔲 🟡 `[Intermediate]` Build a simple prompt versioning system.
- 🔲 🟡 `[Intermediate]` Implement a caching layer for LLM responses.
- ✅ 🟡 `[Intermediate]` Implement semantic caching for LLM queries (cache responses for semantically similar queries).
  <details>
  <summary>💡 Answer</summary>

  [How does Semantic Caching work?](https://outcomeschool.com/blog/how-does-semantic-caching-work)

  </details>
- 🔲 🟡 `[Intermediate]` Write code to detect prompt injection attempts in user inputs.
- 🔲 🟡 `[Intermediate]` Implement an LLM output guardrails system that checks for off-topic responses and PII leakage.
- ✅ 🟡 `[Intermediate]` Build a multi-agent system where agents have different roles and collaborate on a task.
  <details>
  <summary>💡 Answer</summary>

  [Multi-Agent Systems](https://outcomeschool.com/blog/multi-agent-systems)

  </details>

### Behavioral and Scenario-Based Questions

- 🔲 🟢 `[Beginner]` What is AI Engineering, and how does it differ from Machine Learning Engineering?
- 🔲 🟡 `[Intermediate]` How do you decide whether a problem needs AI or a traditional software solution?
- 🔲 🟡 `[Intermediate]` How do you measure the ROI of an AI feature?
- 🔲 🔴 `[Advanced]` How do you handle hallucinations when they occur in a production AI system?
- 🔲 🟡 `[Intermediate]` How do you decide between using an LLM API vs self-hosting an open-source model?
- 🔲 🟡 `[Intermediate]` How do you manage stakeholder expectations for AI projects?
- 🔲 🟡 `[Intermediate]` Describe your approach to debugging a poor-performing RAG system.
- 🔲 🟡 `[Intermediate]` How do you stay current with the rapidly evolving AI landscape?
- 🔲 🟡 `[Intermediate]` How do you balance innovation with reliability in AI systems?
- 🔲 🟡 `[Intermediate]` Tell me about a challenging AI project you worked on. What was the problem? What approach did you take? What trade-offs did you make? What was the outcome?
- 🔲 🔴 `[Advanced]` How would you handle a situation where an AI model produces biased or harmful outputs in production?
- 🔲 🟡 `[Intermediate]` How do you approach cost optimization for an AI system that's exceeding budget?
- 🔲 🟡 `[Intermediate]` Describe a time when you had to choose between model accuracy and latency. How did you make the decision?
- 🔲 🟡 `[Intermediate]` How would you handle a situation where your AI system's quality degrades over time?
- 🔲 🟡 `[Intermediate]` How do you communicate AI limitations to non-technical stakeholders?
- 🔲 🟡 `[Intermediate]` How would you approach building an AI feature with limited labeled data?
- 🔲 🟡 `[Intermediate]` Describe your experience working with cross-functional teams on AI projects.
- 🔲 🟡 `[Intermediate]` Where do you see AI engineering heading in the next 3-5 years?
- 🔲 🟡 `[Intermediate]` Why are you interested in this AI engineering role?
- 🔲 🔴 `[Advanced]` Your PM wants to ship an AI feature with a 15% hallucination rate on edge cases. How do you communicate the risk?
- 🔲 🟡 `[Intermediate]` A non-technical executive asks why your AI feature cannot be 100% accurate. How do you explain LLM limitations?
- 🔲 🟡 `[Intermediate]` You need to choose between a complex agentic system that scores 15% better on benchmarks, or a simpler RAG pipeline that is easier to maintain. How do you decide?

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
