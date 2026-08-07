---
{"dg-publish":true,"permalink":"/embedding/","noteIcon":"","dg-note-properties":{}}
---

See [[LLM\|LLM]]

**What is Embedding?**
An embedding is a numerical vector representation of text that preserves its semantic meaning, allowing AI models to compare, search, and understand relationships between different pieces of text.

**Common Types of Embeddings**
- **Word Embeddings**: Converts individual words into vectors (e.g., Word2Vec, GloVe).
- **Text/Sentence Embeddings**: Converts entire phrases, paragraphs, or documents into a single vector capturing overall meaning.
- **Multimodal Embeddings**: Maps different data types (like an image of a cat and the written word "cat") into the same shared vector space.
____
**How it work?**
- **Similarity becomes measurable.** Items with similar meaning end up close together in the space. "Cat" and "dog" would have vectors closer to each other than "cat" and "airplane."
- **Relationships can be captured.** In good embeddings, directions in the space can represent relationships — the classic example is that `king - man + woman ≈ queen`.
- **Machine learning models need numbers.** Neural networks can't work with raw text or symbols directly, so embeddings turn discrete inputs (words, tokens, users, products, etc.) into numerical form the model can process.
___
**Summary** 

**Embedding, in short:** A numerical representation (a vector of numbers) of data — like a word, sentence, or image — placed in a multi-dimensional space so that similar items end up close together.

**Key points:**
- Turns non-numeric data (text, images, etc.) into numbers a model can process
- Captures meaning/similarity — related items have vectors near each other
- Learned automatically by models from patterns in data
- Powers things like semantic search, recommendations, and RAG systems
