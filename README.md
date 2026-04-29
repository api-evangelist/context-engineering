# Context Engineering

Context engineering is the practice of curating the information that large language models receive at inference time so that the model can perform a task reliably and cost-effectively. It treats the context window as a finite attention budget and looks for the smallest set of high-signal tokens that maximize the likelihood of the desired outcome. Context engineering subsumes and extends prompt engineering, system prompts, tool design, retrieval, agent loops, structured note taking, compaction, and multi-agent decomposition.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/context-engineering/refs/heads/main/apis.yml)

## Tags

- Agents, AI, Anthropic, Compaction, Context Window, LLM, Memory, Prompt Engineering, RAG, Tools

## Timestamps

- **Created:** 2025-01-01
- **Modified:** 2026-04-28

## APIs

### Effective Context Engineering for AI Agents
Anthropic's engineering guide framing context as a finite attention budget and walking through system prompts, tool design, just-in-time retrieval, compaction, structured notes, and multi-agent architectures.

**Human URL:** [Anthropic engineering blog](https://www.anthropic.com/engineering/effective-context-engineering-for-ai-agents)

### Retrieval-Augmented Generation (RAG)
Pattern that augments LLM prompts with passages retrieved at inference time from a vector store, search index, or knowledge base.

**Human URL:** [Original RAG paper](https://arxiv.org/abs/2005.11401)

### Prompt Engineering
The discipline of crafting model instructions and examples to guide model behavior, including chain-of-thought, few-shot, and structured output formats.

**Human URL:** [https://www.promptingguide.ai/](https://www.promptingguide.ai/)

### Agentic Loops and Tool Use
Iterative reasoning patterns where an LLM plans, calls tools, observes results, and refines its plan.

**Human URL:** [Tool use overview](https://docs.anthropic.com/en/docs/build-with-claude/tool-use/overview)

### Long-Horizon Context Strategies
Compaction, structured note taking, and multi-agent decomposition for tasks that exceed the context window.

**Human URL:** [Contextual retrieval](https://www.anthropic.com/news/contextual-retrieval)

## Common Properties

- [Anthropic context engineering](https://www.anthropic.com/engineering/effective-context-engineering-for-ai-agents)
- [Prompting Guide](https://www.promptingguide.ai/)
- [Anthropic prompt engineering](https://docs.anthropic.com/en/docs/build-with-claude/prompt-engineering/overview)
- [LlamaIndex](https://docs.llamaindex.ai/)
- [LangChain RAG](https://python.langchain.com/docs/concepts/rag/)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
