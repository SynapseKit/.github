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

[**Website**](https://synapse-kit.com) · [**Docs**](https://synapsekit.github.io/synapsekit-docs/) · [**Quickstart**](https://synapsekit.github.io/synapsekit-docs/docs/getting-started/quickstart) · [**Discord**](https://discord.gg/PSuAXHRywJ) · [**Contributing**](https://github.com/SynapseKit/SynapseKit/blob/main/CONTRIBUTING.md)

</div>

---

```python
from synapsekit import RAG

rag = RAG(model="gpt-4o-mini", api_key="sk-...")
rag.add("Your document text here")

async for token in rag.stream("Summarise this."):
    print(token, end="", flush=True)
```

**Streaming RAG in 4 lines.**

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

## 33 LLM Providers

<div align="center">

![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat&logo=openai&logoColor=white)
![Anthropic](https://img.shields.io/badge/Anthropic-191919?style=flat&logo=anthropic&logoColor=white)
![Google Gemini](https://img.shields.io/badge/Gemini-4285F4?style=flat&logo=google&logoColor=white)
![Meta](https://img.shields.io/badge/Meta%20Llama-0467DF?style=flat&logo=meta&logoColor=white)
![Mistral](https://img.shields.io/badge/Mistral-FF7000?style=flat&logo=mistral&logoColor=white)
![AWS Bedrock](https://img.shields.io/badge/AWS%20Bedrock-FF9900?style=flat&logo=amazonaws&logoColor=white)
![Azure OpenAI](https://img.shields.io/badge/Azure%20OpenAI-0078D4?style=flat&logo=microsoftazure&logoColor=white)
![Groq](https://img.shields.io/badge/Groq-F55036?style=flat&logo=groq&logoColor=white)
![DeepSeek](https://img.shields.io/badge/DeepSeek-4D6BFE?style=flat&logo=deepseek&logoColor=white)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=flat&logo=ollama&logoColor=white)
![Cohere](https://img.shields.io/badge/Cohere-39594E?style=flat&logo=cohere&logoColor=white)
![Cloudflare](https://img.shields.io/badge/Cloudflare%20AI-F48120?style=flat&logo=cloudflare&logoColor=white)
![Vertex AI](https://img.shields.io/badge/Vertex%20AI-4285F4?style=flat&logo=googlecloud&logoColor=white)
![Together AI](https://img.shields.io/badge/Together%20AI-3C3C3C?style=flat&logo=todoist&logoColor=white)
![Fireworks](https://img.shields.io/badge/Fireworks%20AI-FF4B4B?style=flat&logo=fireworks&logoColor=white)
![Perplexity](https://img.shields.io/badge/Perplexity-20808D?style=flat&logo=perplexity&logoColor=white)
![Cerebras](https://img.shields.io/badge/Cerebras-E3001B?style=flat&logo=cerebras&logoColor=white)
![xAI](https://img.shields.io/badge/xAI%20Grok-000000?style=flat&logo=x&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging%20Face-FFD21E?style=flat&logo=huggingface&logoColor=black)
![OpenRouter](https://img.shields.io/badge/OpenRouter-6E56CF?style=flat&logo=openrouter&logoColor=white)
![Databricks](https://img.shields.io/badge/Databricks-FF3621?style=flat&logo=databricks&logoColor=white)
![SambaNova](https://img.shields.io/badge/SambaNova-EF4D23?style=flat&logo=sambanova&logoColor=white)
![Moonshot](https://img.shields.io/badge/Moonshot%20AI-1A1A2E?style=flat&logo=moon&logoColor=white)
![Zhipu](https://img.shields.io/badge/Zhipu%20AI-2B5BE0?style=flat&logoColor=white)
![AI21 Labs](https://img.shields.io/badge/AI21%20Labs-2D2D2D?style=flat&logoColor=white)
![Writer](https://img.shields.io/badge/Writer-5C4EE5?style=flat&logoColor=white)
![Novita AI](https://img.shields.io/badge/Novita%20AI-FF6B35?style=flat&logoColor=white)
![vLLM](https://img.shields.io/badge/vLLM-2C2C2C?style=flat&logoColor=white)
![LM Studio](https://img.shields.io/badge/LM%20Studio-8B5CF6?style=flat&logoColor=white)
![GPT4All](https://img.shields.io/badge/GPT4All-27AE60?style=flat&logoColor=white)
![llama.cpp](https://img.shields.io/badge/llama.cpp-5C5C5C?style=flat&logoColor=white)
![Aleph Alpha](https://img.shields.io/badge/Aleph%20Alpha-FF4B00?style=flat&logoColor=white)
![Baidu ERNIE](https://img.shields.io/badge/Baidu%20ERNIE-2932E1?style=flat&logo=baidu&logoColor=white)

</div>

---

## 53 Document Loaders

<div align="center">

**Files & Docs**

![PDF](https://img.shields.io/badge/PDF-EC1C24?style=flat&logo=adobeacrobatreader&logoColor=white)
![Word](https://img.shields.io/badge/Word-2B579A?style=flat&logo=microsoftword&logoColor=white)
![Excel](https://img.shields.io/badge/Excel-217346?style=flat&logo=microsoftexcel&logoColor=white)
![PowerPoint](https://img.shields.io/badge/PowerPoint-B7472A?style=flat&logo=microsoftpowerpoint&logoColor=white)
![Markdown](https://img.shields.io/badge/Markdown-000000?style=flat&logo=markdown&logoColor=white)
![CSV](https://img.shields.io/badge/CSV-217346?style=flat&logo=files&logoColor=white)
![JSON](https://img.shields.io/badge/JSON-000000?style=flat&logo=json&logoColor=white)
![HTML](https://img.shields.io/badge/HTML-E34F26?style=flat&logo=html5&logoColor=white)
![EPUB](https://img.shields.io/badge/EPUB-2C2C2C?style=flat&logoColor=white)
![LaTeX](https://img.shields.io/badge/LaTeX-008080?style=flat&logo=latex&logoColor=white)
![YAML](https://img.shields.io/badge/YAML-CB171E?style=flat&logoColor=white)
![XML](https://img.shields.io/badge/XML-005FAD?style=flat&logoColor=white)

**Cloud Storage**

![AWS S3](https://img.shields.io/badge/AWS%20S3-FF9900?style=flat&logo=amazons3&logoColor=white)
![Google Drive](https://img.shields.io/badge/Google%20Drive-4285F4?style=flat&logo=googledrive&logoColor=white)
![OneDrive](https://img.shields.io/badge/OneDrive-0078D4?style=flat&logo=microsoftonedrive&logoColor=white)
![Dropbox](https://img.shields.io/badge/Dropbox-0061FF?style=flat&logo=dropbox&logoColor=white)
![Azure Blob](https://img.shields.io/badge/Azure%20Blob-0078D4?style=flat&logo=microsoftazure&logoColor=white)
![GCS](https://img.shields.io/badge/Google%20Cloud%20Storage-4285F4?style=flat&logo=googlecloud&logoColor=white)

**Databases**

![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat&logo=mongodb&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat&logo=redis&logoColor=white)
![Elasticsearch](https://img.shields.io/badge/Elasticsearch-005571?style=flat&logo=elasticsearch&logoColor=white)
![DynamoDB](https://img.shields.io/badge/DynamoDB-4053D6?style=flat&logo=amazondynamodb&logoColor=white)
![BigQuery](https://img.shields.io/badge/BigQuery-4285F4?style=flat&logo=googlebigquery&logoColor=white)
![Snowflake](https://img.shields.io/badge/Snowflake-29B5E8?style=flat&logo=snowflake&logoColor=white)
![Airtable](https://img.shields.io/badge/Airtable-18BFFF?style=flat&logo=airtable&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=flat&logo=supabase&logoColor=white)
![Parquet](https://img.shields.io/badge/Parquet-50ABF1?style=flat&logo=apacheparquet&logoColor=white)

**Productivity & CRM**

![Notion](https://img.shields.io/badge/Notion-000000?style=flat&logo=notion&logoColor=white)
![Confluence](https://img.shields.io/badge/Confluence-172B4D?style=flat&logo=confluence&logoColor=white)
![Jira](https://img.shields.io/badge/Jira-0052CC?style=flat&logo=jira&logoColor=white)
![Google Sheets](https://img.shields.io/badge/Google%20Sheets-34A853?style=flat&logo=googlesheets&logoColor=white)
![HubSpot](https://img.shields.io/badge/HubSpot-FF7A59?style=flat&logo=hubspot&logoColor=white)
![Salesforce](https://img.shields.io/badge/Salesforce-00A1E0?style=flat&logo=salesforce&logoColor=white)
![Trello](https://img.shields.io/badge/Trello-0052CC?style=flat&logo=trello&logoColor=white)
![Microsoft Teams](https://img.shields.io/badge/Teams-6264A7?style=flat&logo=microsoftteams&logoColor=white)

**Communication & Social**

![Slack](https://img.shields.io/badge/Slack-4A154B?style=flat&logo=slack&logoColor=white)
![Discord](https://img.shields.io/badge/Discord-5865F2?style=flat&logo=discord&logoColor=white)
![Reddit](https://img.shields.io/badge/Reddit-FF4500?style=flat&logo=reddit&logoColor=white)
![Twitter/X](https://img.shields.io/badge/Twitter%2FX-000000?style=flat&logo=x&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white)
![RSS](https://img.shields.io/badge/RSS-FFA500?style=flat&logo=rss&logoColor=white)

**Web & Research**

![Wikipedia](https://img.shields.io/badge/Wikipedia-000000?style=flat&logo=wikipedia&logoColor=white)
![ArXiv](https://img.shields.io/badge/ArXiv-B31B1B?style=flat&logo=arxiv&logoColor=white)
![PubMed](https://img.shields.io/badge/PubMed-326599?style=flat&logoColor=white)
![YouTube](https://img.shields.io/badge/YouTube-FF0000?style=flat&logo=youtube&logoColor=white)
![Sitemap](https://img.shields.io/badge/Sitemap-4285F4?style=flat&logo=googlesearchconsole&logoColor=white)
![Obsidian](https://img.shields.io/badge/Obsidian-483699?style=flat&logo=obsidian&logoColor=white)

**Media**

![Audio](https://img.shields.io/badge/Audio%20%2F%20Whisper-000000?style=flat&logo=audacity&logoColor=white)
![Video](https://img.shields.io/badge/Video-FF0000?style=flat&logo=ffmpeg&logoColor=white)

</div>

---

## 11 Vector Stores

<div align="center">

![In-Memory](https://img.shields.io/badge/InMemory%20%2B%20npz-22c55e?style=flat&logoColor=white)
![ChromaDB](https://img.shields.io/badge/ChromaDB-FF6719?style=flat&logoColor=white)
![FAISS](https://img.shields.io/badge/FAISS-3178C6?style=flat&logo=meta&logoColor=white)
![Qdrant](https://img.shields.io/badge/Qdrant-DC244C?style=flat&logo=qdrant&logoColor=white)
![Pinecone](https://img.shields.io/badge/Pinecone-000000?style=flat&logo=pinecone&logoColor=white)
![Weaviate](https://img.shields.io/badge/Weaviate-5CB85C?style=flat&logoColor=white)
![PGVector](https://img.shields.io/badge/PGVector-4169E1?style=flat&logo=postgresql&logoColor=white)
![Milvus](https://img.shields.io/badge/Milvus-00A1EA?style=flat&logo=milvus&logoColor=white)
![LanceDB](https://img.shields.io/badge/LanceDB-F7B731?style=flat&logoColor=white)
![SQLite-vec](https://img.shields.io/badge/SQLite--vec-003B57?style=flat&logo=sqlite&logoColor=white)
![MongoDB Atlas](https://img.shields.io/badge/MongoDB%20Atlas-47A248?style=flat&logo=mongodb&logoColor=white)

</div>

---

## What's in this org

| Repo | What it is |
|---|---|
| [**SynapseKit/SynapseKit**](https://github.com/SynapseKit/SynapseKit) | The core library — RAG, agents, graph workflows, 33 LLM providers |
| [**SynapseKit/synapsekit-docs**](https://github.com/SynapseKit/synapsekit-docs) | Documentation site (Docusaurus), live at [synapsekit.github.io/synapsekit-docs](https://synapsekit.github.io/synapsekit-docs/) |
| [**SynapseKit/synapsekit-ui**](https://github.com/SynapseKit/synapsekit-ui) | Marketing website, live at [synapse-kit.com](https://synapse-kit.com) |
| [**SynapseKit/evalci**](https://github.com/SynapseKit/evalci) | Hosted eval runner — run SynapseKit eval suites in CI via GitHub Action |

---

## Why SynapseKit

> *"LangChain for people who hate LangChain."*

| | SynapseKit | LangChain | LlamaIndex |
|---|---|---|---|
| Hard deps | **2** | 50+ | 20+ |
| Install size | **~5 MB** | ~200 MB+ | ~100 MB+ |
| Async-native | **✅ Default** | ⚠️ Partial | ⚠️ Partial |
| Streaming | **✅ Default** | ⚠️ Varies | ⚠️ Varies |
| Cost tracking | **✅ Built-in** | ❌ SaaS | ❌ No |
| Evaluation / EvalCI | **✅ CLI + GitHub Action** | ❌ SaaS | ⚠️ Built-in |
| Graph workflows | **✅ Built-in** | ⚠️ Separate pkg | ❌ No |
| Agent federation | **✅ Built-in** | ❌ No | ❌ No |
| Reasoning LLMs | **✅ Unified adapter** | ⚠️ Manual | ⚠️ Manual |
| Structured output | **✅ Provider-agnostic** | ⚠️ Provider-specific | ⚠️ Provider-specific |
| Agent memory | **✅ 4 built-in backends** | ⚠️ Community plugins | ⚠️ Community plugins |
| Observability | **✅ Prometheus + Grafana** | ❌ No | ❌ No |
| Stack traces | **Your code** | Framework internals | Framework internals |
| License | **Apache 2.0** | MIT | MIT |

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

Browse [good first issues](https://github.com/SynapseKit/SynapseKit/issues?q=label%3A%22good+first+issue%22) · Read the [Contributing Guide](https://github.com/SynapseKit/SynapseKit/blob/main/CONTRIBUTING.md) · Join [Discord](https://discord.gg/PSuAXHRywJ)

<div align="center">

**[⭐ Star the repo](https://github.com/SynapseKit/SynapseKit) if SynapseKit saves you time.**

</div>
