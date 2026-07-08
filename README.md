# Hi, I'm Sandeep 👋

**I work on AI agent infrastructure** — the runtime layer that makes agents dependable: memory and semantic recall, streaming, tool orchestration, and background execution. I'm an active contributor to [Mastra](https://github.com/mastra-ai/mastra) (25k+ ⭐) with **12 merged PRs** across core, `ai-sdk`, and Studio. Previously: AI Engineer at **AiRA** (agent orchestration, memory, RAG) and AI Research Intern at **IIT Kharagpur** (multimodal LLM fine-tuning — 75% accuracy on circuit-generation tasks where base models scored ~0%).

📍 Bengaluru, India · 🌐 [Portfolio](https://devsandy.vercel.app/) · 💼 [LinkedIn](https://www.linkedin.com/in/sandeep-singh-445058254/) · 📫 sandy1711003@gmail.com

## 🔧 Highlight contributions

| Contribution | Impact |
| --- | --- |
| [mastra #17818](https://github.com/mastra-ai/mastra/pull/17818) — semantic recall not injected for signal-delivered user messages | Long-term memory recall now fires on every user-message path, not just direct sends |
| [mastra #18191](https://github.com/mastra-ai/mastra/pull/18191) — duplicate stream events when observing an in-progress run | Observing/replaying a live agent run no longer delivers duplicate chunks at the replay→live boundary |
| [mastra #18454](https://github.com/mastra-ai/mastra/pull/18454) — store tool-level `background` config on the Tool instance | Per-tool background-execution config survives registration and is honored by the runtime |
| [mastra #18592](https://github.com/mastra-ai/mastra/pull/18592) — apply editor-stored overrides in `chatRoute` | Studio-configured agent overrides now apply to ai-sdk chat endpoints |
| [mastra #18015](https://github.com/mastra-ai/mastra/pull/18015) / [#18404](https://github.com/mastra-ai/mastra/pull/18404) — Studio preserved code-agent instructions & tools on save | Fixed two data-loss bugs in Studio's agent editor |
| [mastra #18252](https://github.com/mastra-ai/mastra/pull/18252) — concurrent-init race in `@mastra/google-cloud-pubsub` | Ungrouped topics initialize safely under concurrent first use |
| [cal.com #29355](https://github.com/calcom/cal.diy/pull/29355) — full BigBlueButton video integration | 912 LOC, 26 files, 32 unit tests: VideoApiAdapter, checksum-signed client, encrypted credential storage |
| [n8n #20254](https://github.com/n8n-io/n8n/pull/20254) — build failure on directory paths with spaces | OpenAPI bundling works cross-platform, unblocking Windows contributors |

Full Mastra activity → [all PRs by me](https://github.com/mastra-ai/mastra/pulls?q=author%3ASandy-1711)

## 🚀 Projects

- **[Samagra](https://play.google.com/store/apps/details?id=com.indigle.samagra)** — campus ERP platform I co-founded under Indigle: React Native + Node.js/Express + MongoDB, **10,000+ active users**, 150k+ monthly API requests on a zero-cost serverless backend.
- **[EmailPartner](https://github.com/Sandy-1711/EmailPartner)** — turns incoming Gmail into live AI cards (headline, summary, illustration, voice narration): Gmail watch → Pub/Sub push → durable worker queue → Gemini.
- **[Web-Aware RAG Engine](https://github.com/Sandy-1711/Web-Aware-Rag-Engine)** — async web ingestion and semantic search with load-balanced FastAPI replicas and a Next.js 15 frontend.
- **[IntelliCommerce](https://github.com/Sandy-1711/IntelliCommerce)** — intent-routing e-commerce chatbot across microservices with Pinecone-backed RAG.

## 🛠 Stack

`Python` `TypeScript` `FastAPI` `Node.js` `Next.js` `React Native` `MongoDB` `PostgreSQL` `Redis` `Docker` `Mastra` `LangChain` `Langfuse` `promptfoo`
