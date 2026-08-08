### Hi, I'm Olga 👋

I build tooling for LLM agents — evals, context-cost analysis, and the harness
that keeps them reliable. Python. Self-taught. Ternopil, Ukraine.

#### 🔦 [ctxprofile](https://github.com/Evge14n/ctxprofile)

An offline CLI that costs an LLM request **per context component** and gates that
cost in CI.

I pointed it at four popular MCP servers. Before you type a single character,
your request already carries **46 tool definitions, ~8,300 tokens, ≈$0.04 — on
every call**. Tool schemas were 99.8% of that input, and one single tool cost
more than an entire twelve-tool server.
[The measurement.](https://github.com/Evge14n/ctxprofile/blob/main/docs/case-study-mcp.md)

`Python` · `zero runtime deps` · `62 tests` · `mypy --strict` · optional MCP server · `MIT`

#### Currently

Working on LLM **evaluation** and **context engineering** — measuring what agents
actually do, not what we assume. I care about the unglamorous version of
reliability: tools that do what they say and can be inspected.

#### Working with

Python (asyncio) · LLM/RAG (OpenAI, pgvector, LangChain) · Model Context Protocol ·
evals & token-cost analysis · aiogram · Linux · Docker

<sub>Top-16 of 2,880 in AI &amp; Machine Learning on Freelancehunt · 100% completion</sub>
