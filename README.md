# Awesome Research Agent

A curated list of papers, projects, and resources for research agents.
<p align="center">
<img src="assets/agent.webp" width="480px"/>   
</p>
<p align="center">
Build a digital assistant on your screen. Generated by <a href="https://openai.com/index/dall-e-3/">DALL-E-3</a>.
</p>

**WELCOME CONTRIBUTE!**

🔥 This project is actively maintained, and we welcome your contributions. If you have any suggestions, such as missing papers or information, please feel free to open an issue or submit a pull request.

## Relevant Survey
+ [A Survey of Generative Search and Recommendation in the Era of Large Language Models](https://arxiv.org/abs/2404.16924) (Apr.2024)
  
+ [When Search Engine Services meet Large Language Models: Visions and Challenges](https://arxiv.org/abs/2407.00128) (Jun.2024)

+ [Large Language Models for Information Retrieval: A Survey](https://arxiv.org/abs/2308.07107) (Sep.2024)



## Benchmark
+ [SWE-bench: Can Language Models Resolve Real-World GitHub Issues?](https://arxiv.org/abs/2310.06770)(Oct.2023)
  
+ [GAIA: a benchmark for General AI Assistants](https://arxiv.org/abs/2311.12983) (Nov.2023)

+ [Learning to Ask: When LLM Agents Meet Unclear Instruction](https://arxiv.org/abs/2409.00557v3) (Aug.2024)

+ [Humanity's Last Exam](https://arxiv.org/abs/2501.14249) (Jan.2025)
  
+ **[MLGym: A New Framework and Benchmark for Advancing AI Research Agents](https://arxiv.org/abs/2502.14499) (Feb. 2025)

+ [Retrieval Models Aren't Tool-Savvy: Benchmarking Tool Retrieval for Large Language Models](https://arxiv.org/abs/2503.01763) (Mar.2025)

## Close Source Research Agent
+ **[Google Gemini Deep Research](https://gemini.google/overview/deep-research/) (Dec.2024)

+ **[Open AI Deep Research](https://openai.com/index/introducing-deep-research/) (Feb.2025)

+ **[Perplexity Deep Research](https://www.perplexity.ai/hub/blog/introducing-perplexity-deep-research) (Feb.2025)

+ **[Grok Deep Search](https://x.ai/news/grok-3) (March. 2025)

## Deep Research Agent (final):
+ **[Agentic Reasoning: Reasoning LLMs with Tools for the Deep Research](https://arxiv.org/abs/2502.04644) (Feb.2025)
  
  store reasoning in the knowledge graph， generate reasoning and answer✅


## Deep Research Agent
+ **[Agentic Reasoning: Reasoning LLMs with Tools for the Deep Research](https://arxiv.org/abs/2502.04644) (Feb.2025)

+ [AgentRxiv: Towards Collaborative Autonomous Research](https://agentrxiv.github.io/) (Mar.2025)

+ [Agent-R1: Training Powerful LLM Agents with End-to-End Reinforcement Learning](https://github.com/0russwest0/Agent-R1) (Mar.2025)

## Retrieval/Search Augmented Agent Framework
+ [Assisting in Writing Wikipedia-like Articles From Scratch with Large Language Models](https://arxiv.org/abs/2402.14207) (Jul.2024)

+ **[OPEN-RAG: Enhanced Retrieval-Augmented Reasoning with Open-Source Large Language Models](https://arxiv.org/abs/2410.01782) (Oct.2024)

+ [Chain-of-Retrieval Augmented Generation](https://arxiv.org/abs/2501.14342) (Jan.2025)

+ **[Search-o1: Agentic Search-Enhanced Large Reasoning Models](https://arxiv.org/abs/2501.05366) (Jan.2025)

+ [FlashRAG: A Modular Toolkit for Efficient Retrieval-Augmented Generation Research](https://arxiv.org/abs/2405.13576) (Feb.2025)

+ [DeepRAG: Thinking to Retrieval Step by Step for Large Language Models](https://arxiv.org/abs/2502.01142) (Feb.2025)

+ [Toward Agentic AI: Generative Information Retrieval Inspired Intelligent Communications and Networking](https://arxiv.org/abs/2502.16866) (Feb.2025)

## Toolcall Agent Framework
+ [Agent S: An Open Agentic Framework that Uses Computers Like a Human](https://arxiv.org/abs/2410.08164) (Oct.2024)

+ [Open AI Operator](https://openai.com/index/introducing-operator/) (Jan.2025)

+ [AutoAgent: A Fully-Automated and Zero-Code Framework for LLM Agents](https://arxiv.org/pdf/2502.05957) (Feb. 2025)

+ [Agent S2: An Open, Modular, and Scalable Framework for Computer Use Agents](https://www.simular.ai/agent-s2) (Mar.2025)

+ **[OWL: Optimized Workforce Learning for General Multi-Agent Assistance in Real-World Task Automation](https://github.com/camel-ai/owl/tree/main?tab=readme-ov-file) (Mar.2025)

+ **[OpenManus](https://github.com/mannaandpoem/OpenManus) (Mar. 2025)

+ [START: Self-taught Reasoner with Tools](https://arxiv.org/abs/2503.04625) (Mar.2025)

## SFT
+ [START: Self-taught Reasoner with Tools](https://arxiv.org/abs/2503.04625) (Mar.2025)

  infer with tool -> hint-rft (rule-based scoring and filtering to get sft data) -> sft -> rft

## Reinforcement Learning - no tool， only search engine（paper）. only one repo - (agent-r1)
+ [DeepRetrieval: Powerful Query Generation for Information Retrieval with Reinforcement Learning](https://arxiv.org/abs/2503.00223) (Feb.2025)
  Leverage search query using RL is not relevant to the research agent.

+ [ReSearch: Learning to Reason with Search for LLMs via Reinforcement Learning](https://github.com/Agent-RL/ReSearch) (Mar.2025)
  
  grpo, similar to search-r1, Iteratively perform think - search query generation/answer generation loop. masking retrieval results

  reward： andwer reward(f1) -- short answer.. format reward

+ [R1-Searcher: Incentivizing the Search Capability in LLMs via Reinforcement Learning](https://arxiv.org/abs/2503.05592) (Mar.2025)
  
+ [Search-R1: Training LLMs to Reason and Leverage Search Engines with Reinforcement Learning](https://arxiv.org/abs/2503.09516) (Mar.2025)

  add search query into template, call llm iteratly to implement multi-turn search. reward model is exact string matching (rule-based outcome reward to avoid reward hacking). grpo, ppo.

+ [Agent-R1: Training Powerful LLM Agents with End-to-End Reinforcement Learning](https://github.com/0russwest0/Agent-R1) (Mar.2025)

+ [Test-time Scaling Methods (Test-Time): CR-Planner [19], ReARTeR [23]]



