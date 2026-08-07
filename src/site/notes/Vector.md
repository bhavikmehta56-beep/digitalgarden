---
{"dg-publish":true,"permalink":"/vector/","noteIcon":"","dg-note-properties":{}}
---

See [[LLM\|LLM]]

**What is Vector ?**
A **vector in an LLM** is a numerical representation of the meaning of text, allowing the model to compare, search, and reason about language using mathematics instead of raw words.
_____________
**How it work ?**
Computers can't understand words directly, so each token gets converted into a vector — something like:
"cat" → [0.21, -0.45, 0.88, ..., 0.02]   (e.g., 768 or 4096 numbers long)
These numbers aren't arbitrary. They're learned during training so that words with similar meanings end up with similar vectors — geometrically "close" to each other in that multi-dimensional space.

The process looks like this:

```
Text
   │
   ▼
Tokenizer
   │
   ▼
Tokens
   │
   ▼
Embedding Model
   │
   ▼
Vectors (Embeddings)
   │
   ▼
LLM processes these vectors
```


------
**Summary**
A **vector** in an LLM is a numerical representation of the meaning of text. The model converts words or sentences into vectors (lists of numbers) so it can compare meanings, identify similarities, and generate accurate responses.

Flow:
Text → Tokens → Vectors (Embeddings) → LLM Processing → Output