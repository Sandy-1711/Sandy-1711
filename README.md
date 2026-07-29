# Hi, I'm Sandeep 👋

**I work on AI agent infrastructure** — the runtime layer that makes agents dependable: memory and semantic recall, streaming, tool orchestration, and background execution. I'm an active contributor to [Mastra](https://github.com/mastra-ai/mastra) (25k+ ⭐) with **12 merged PRs** across core, `ai-sdk`, and Studio. Previously: AI Engineer at **AiRA** (agent orchestration, memory, RAG) and AI Research Intern at **IIT Kharagpur** (multimodal LLM fine-tuning — 75% accuracy on circuit-generation tasks where base models scored ~0%).

📍 Bengaluru, India ·  💼 [LinkedIn](https://www.linkedin.com/in/sandeep-singh-445058254/) · 📫 sandy1711003@gmail.com · 🌐 [Portfolio](https://devsandy.vercel.app/)

## 🔧 Highlight contributions

Explained so anyone can follow — each row is what I did and why it matters, in plain English.

| Contribution | What it means |
| --- | --- |
| **The agent stopped forgetting** · [mastra #17818](https://github.com/mastra-ai/mastra/pull/17818) | AI agents keep a long-term memory, but on one type of incoming message they weren't checking it before replying — so they'd answer as if they'd forgotten past context. Now they look it up on **every** message. |
| **No more double-typed replies** · [mastra #18191](https://github.com/mastra-ai/mastra/pull/18191) | When you open an answer that's already being generated and watch it stream in, some of the text was arriving **twice**. Fixed the duplicate delivery. |
| **Background tools actually run in the background** · [mastra #18454](https://github.com/mastra-ai/mastra/pull/18454) | You can mark a tool to run in the background so the agent doesn't sit and wait for it — but that setting was being thrown away. Now it's saved and respected. |
| **Your agent settings actually apply** · [mastra #18592](https://github.com/mastra-ai/mastra/pull/18592) | Tweaks you made to an agent in the visual editor weren't being used when you chatted with it through the API. Now they are. |
| **Saving no longer wipes your work** · [mastra #18015](https://github.com/mastra-ai/mastra/pull/18015) / [#18404](https://github.com/mastra-ai/mastra/pull/18404) | Saving an agent in the editor was erasing its instructions and tools. Fixed two of those data-loss bugs. |
| **Servers don't crash on simultaneous startup** · [mastra #18252](https://github.com/mastra-ai/mastra/pull/18252) | When two servers booted at the exact same moment, they could collide setting up the same message channel and fail. Fixed the race so startup is safe. |
| **Added BigBlueButton video calls to cal.com** · [cal.com #29355](https://github.com/calcom/cal.diy/pull/29355) | A whole new video-meeting option: booking a meeting can now auto-create a BigBlueButton room. Full integration — 912 lines of code, 32 tests. |
| **Builds work even with a space in the folder path** · [n8n #20254](https://github.com/n8n-io/n8n/pull/20254) | The project wouldn't build if its folder path had a space in it (common on Windows, like `My Documents`). Fixed so anyone can build it. |

Full Mastra activity → [all PRs by me](https://github.com/mastra-ai/mastra/pulls?q=author%3ASandy-1711)

## 🚀 Projects

- **[Samagra](https://play.google.com/store/apps/details?id=com.indigle.samagra)** — campus ERP platform I co-founded under Indigle: React Native + Node.js/Express + MongoDB, **10,000+ active users**, 150k+ monthly API requests on a zero-cost serverless backend.
- **[EmailPartner](https://github.com/Sandy-1711/EmailPartner)** — turns incoming Gmail into live AI cards (headline, summary, illustration, voice narration): Gmail watch → Pub/Sub push → durable worker queue → Gemini.
- **[Web-Aware RAG Engine](https://github.com/Sandy-1711/Web-Aware-Rag-Engine)** — async web ingestion and semantic search with load-balanced FastAPI replicas and a Next.js 15 frontend.
- **[IntelliCommerce](https://github.com/Sandy-1711/IntelliCommerce)** — intent-routing e-commerce chatbot across microservices with Pinecone-backed RAG.

## 🛠 Stack

`Python` `TypeScript` `FastAPI` `Node.js` `Next.js` `React Native` `MongoDB` `PostgreSQL` `Redis` `Docker` `Mastra` `LangChain` `Langfuse` `promptfoo`
