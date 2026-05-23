<div align="center">
  <img src="https://raw.githubusercontent.com/SynapseKit/SynapseKit/main/assets/banner.svg" alt="SynapseKit" width="100%"/>
</div>

<div align="center">

[![PyPI version](https://img.shields.io/pypi/v/synapsekit?color=22c55e&label=pypi&logo=pypi&logoColor=white)](https://pypi.org/project/synapsekit/)
[![Python](https://img.shields.io/badge/python-3.10%2B-22c55e?logo=python&logoColor=white)](https://www.python.org/)
[![License: Apache 2.0](https://img.shields.io/badge/license-Apache%202.0-22c55e)](https://github.com/SynapseKit/SynapseKit/blob/main/LICENSE)
[![Tests](https://img.shields.io/badge/tests-4139%20passing-22c55e?logo=pytest&logoColor=white)](https://github.com/SynapseKit/SynapseKit)
[![Downloads](https://static.pepy.tech/badge/synapsekit)](https://pepy.tech/project/synapsekit)
[![Discord](https://img.shields.io/discord/1488136255597182988?logo=discord&logoColor=white&label=discord)](https://discord.gg/PSuAXHRywJ)

**Build production LLM apps with 2 dependencies.**

Async-native RAG, Agents, and Graph Workflows — no magic, no SaaS, no bloat.

[**Docs**](https://synapsekit.github.io/synapsekit-docs/) · [**Quickstart**](https://synapsekit.github.io/synapsekit-docs/docs/getting-started/quickstart) · [**Discord**](https://discord.gg/PSuAXHRywJ) · [**Contributing**](https://github.com/SynapseKit/SynapseKit/blob/main/CONTRIBUTING.md)

</div>

---

```python
from synapsekit import RAG

rag = RAG(model="gpt-4o-mini", api_key="sk-...")
rag.add("SynapseKit is a production-grade LLM framework.")

async for token in rag.stream("What is SynapseKit?"):
    print(token, end="", flush=True)
```

**That's it. Streaming RAG in 4 lines.**

---

<div align="center">

<table>
<tr>
<td align="center"><h3>33</h3>LLM Providers</td>
<td align="center"><h3>53</h3>Document Loaders</td>
<td align="center"><h3>11</h3>Vector Stores</td>
<td align="center"><h3>48+</h3>Built-in Tools</td>
<td align="center"><h3>4139</h3>Tests passing</td>
</tr>
</table>

</div>

---

## What's in this org

| Repo | What it is |
|---|---|
| [**SynapseKit/SynapseKit**](https://github.com/SynapseKit/SynapseKit) | The core library — RAG, agents, graph workflows, 33 LLM providers |
| [**SynapseKit/synapsekit-docs**](https://github.com/SynapseKit/synapsekit-docs) | Documentation site (Docusaurus), live at [synapsekit.github.io/synapsekit-docs](https://synapsekit.github.io/synapsekit-docs/) |
| [**SynapseKit/evalci**](https://github.com/SynapseKit/evalci) | Hosted eval runner — run SynapseKit eval suites in CI via GitHub Action |

---

## Why SynapseKit

> *"LangChain for people who hate LangChain."*

<table>
<tr>
<td width="50%">

**The problem:** LangChain and LlamaIndex are heavy — 50+ dependencies, hidden chains, magic callbacks, and basic observability locked behind a SaaS subscription.

**The fix:** SynapseKit gives you everything you need to build production LLM apps with **2 core dependencies** and plain Python you can actually read and debug.

</td>
<td width="50%">

| | SynapseKit | LangChain |
|---|---|---|
| Hard deps | **2** | 50+ |
| Async-native | **✅** | ⚠️ Partial |
| Cost tracking | **✅ Built-in** | ❌ SaaS |
| Stack traces | **Your code** | Framework |

</td>
</tr>
</table>

---

## Get started

```bash
pip install synapsekit[openai]
```

```python
from synapsekit import RAG

rag = RAG(model="gpt-4o-mini", api_key="sk-...")
rag.add("Your document text here")
print(rag.ask_sync("Summarise this."))
```

Full docs → [synapsekit.github.io/synapsekit-docs](https://synapsekit.github.io/synapsekit-docs/)

---

## Contributing

We welcome contributions of all sizes — new LLM providers, loaders, bug fixes, docs, and tests. Start here:

1. Browse [good first issues](https://github.com/SynapseKit/SynapseKit/issues?q=label%3A%22good+first+issue%22)
2. Read the [Contributing Guide](https://github.com/SynapseKit/SynapseKit/blob/main/CONTRIBUTING.md)
3. Join [Discord](https://discord.gg/PSuAXHRywJ) to ask questions

<div align="center">

**[⭐ Star the repo](https://github.com/SynapseKit/SynapseKit) if SynapseKit saves you time.**

</div>
