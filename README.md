# Context Engineering

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
