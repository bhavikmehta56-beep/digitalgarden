---
{"dg-publish":true,"permalink":"/rag/","dg-note-properties":{"permalink":"AI study"}}
---

See [[Machine Learning\|Machine Learning]]

**What is RAG? Explain in details**
RAG combines a language model with an external knowledge source to produce more accurate, up-to-date, and grounded responses. Instead of relying only on what the model learned during training (which is frozen at a cutoff date), RAG lets the model pull in relevant information at query time.

![RAG Process.png\|499](/img/user/Image/RAG%20Process.png)
**How it works**
1. **Retrieve** — On a query, the system searches an external knowledge base (documents, database, internal files, website, etc.) for relevant chunks of text. Typically done via vector embeddings + similarity search, sometimes combined with keyword search.
2. **Augment** — Retrieved passages are inserted into the prompt alongside the user's question, giving the model extra context.
3. **Generate** — The model produces an answer using both its general knowledge and the retrieved information.

**Why it's useful**
- **Reduces hallucination** — answers can be grounded in real source material
- **Keeps knowledge current** — update the knowledge base without retraining the model
- **Enables private/domain-specific knowledge** — e.g., internal company docs the model never saw during training
- **Supports citations** — the system can reference which passages informed the answer

**Typical use cases**
- Internal-docs chatbots / support tools
- Product manual Q&A
- Research assistants over a paper/document set
- Search engines with cited summaries
 ------
**Summary**

**Retrieval-Augmented Generation (RAG)** combines an LLM with an external retrieval system. When a user asks a question, RAG first retrieves the most relevant information from a knowledge source (such as PDFs, databases, or web documents) and then provides that information to the LLM to generate a more accurate, context-aware, and up-to-date response. This makes RAG especially useful for applications that require current or organization-specific knowledge, such as customer support, enterprise search, and document question answering.