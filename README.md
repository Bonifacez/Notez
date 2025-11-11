# Notez — A Privacy‑First AI Writing & Knowledge Activation Space

[中文版本 Chinese README](Readme-zh.md)

Official Website: [notezapp.com](https://notezapp.com)  •  Download: [notezapp.com/download](https://notezapp.com/download)

Notez is a serious writing environment that combines a local knowledge base with trustworthy AI assistance. Instead of pushing your documents to a black‑box cloud, Notez keeps the full chain (documents, indices, embeddings, citations) local by default while selectively and minimally invoking external language models only with pruned relevant fragments. The goal is not “generate everything for you,” but to reduce friction across research, drafting, verification, and long‑form iteration.

## Why Notez?

Traditional note apps, cloud docs, and generic AI writing tools fail in sensitive or deep writing scenarios: privacy risk, dormant archives, shallow AI output, citation fragility, and style drift. Notez addresses four pillars:

1. Private‑First Boundary: Local‑first storage and processing; explicit preview of outbound AI context.
2. Knowledge Asset Activation: Documents are decomposed into semantic fragments that participate in completion, chat, retrieval, and citation.
3. Semantic Fusion Pipeline: Retrieval + validation + constrained generation + source binding—not just “call a model”.
4. Traceability & Consistency: Every generated segment can carry citations; pin key viewpoints to stabilize future drafts.

## Core Features (High Level)

- Local Knowledge Base & Indexing (Markdown, PDF, Docx, Txt, folders & sync)
- AI Auto‑Completion with domain‑aware suggestions referencing your own materials
- Contextual AI Chat (multi‑turn, @ targeting, citation tracing, pin important answers)
- Smart Retrieval & Citation (source provenance one click away)
- Document Import Pipeline (parsing → structure extraction → chunking → embedding → keyword index)
- Export to PDF / Word with structural fidelity
- Private model configuration (OpenAI, Azure, or self‑hosted / local engines)
- Multi‑language UI & docs (EN / 中文)

## Quick Glimpse of Workflow

1. Import / Sync a folder of research or legal documents.
2. Configure at least one chat model and one embedding model (e.g. `gpt-5` + `text-embedding-3-small`).
3. Start drafting; auto‑completion offers context‑aware continuations.
4. Use AI Chat with @ tags to pull precise documents; pin validated conclusions.
5. Insert cited fragments; verify provenance; iteratively refine.
6. Export polished draft to PDF or Word.

## Privacy & Data Handling Philosophy

While this web repo exposes architecture and docs, the Notez application enforces local‑first processing for user materials. External model calls send only minimal relevant fragments; full documents, indices, and vector stores remain local. Users can self‑host models for maximal control.

## FAQ (Condensed)

| Question | Answer |
| -------- | ------ |
| Does Notez upload my docs? | No, storage & indexing are local by default. |
| Can I use a self‑hosted model? | Yes—configure a custom URL + API key. |
| What file types are supported? | Markdown, PDF (text layer), Docx, Txt (others planned). |
| How are citations shown? | Inline markers with jump‑to‑source, export planned. |

## Contact & Links

- Website: [https://notezapp.com](https://notezapp.com)
- Download: [https://notezapp.com/download](https://notezapp.com/download)
- Issues: Use GitHub Issues for bug reports & doc suggestions

If you read Chinese: 请点击右上角的 “中文版本” 链接查看中文 README。

---

Serious writing deserves tools that amplify thinking rather than replace it. Welcome to Notez.
