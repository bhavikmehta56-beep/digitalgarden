---
{"dg-publish":true,"permalink":"/token/","noteIcon":"","dg-note-properties":{}}
---

See [[LLM\|LLM]]

**What is Token  ?**
A "token" is a chunk of text that a language model like me processes as its basic unit — smaller than a word in many cases, but not quite a single letter either.
- **1 Token** $\approx$ 4 characters of English text.
- **1 Token** $\approx$ 0.75 words.
- **100 Tokens** $\approx$ 75 words.
For example, the word `"indivisible"` might be broken down into three sub-word tokens: `"in"`, `"divis"`, and `"ible"`.
_____
**How it work ?**
Tokenization is the translation layer between raw human text and mathematical vectors.
  1. Subword Splitting: The tokenizer algorithm (such as Byte-Pair Encoding, or BPE) evaluates text and splits common words into single tokens, while rare, complex, or compound words are split into sub-word fragments.

  2. Vocabulary Lookup: Each unique token is mapped to a static integer ID using the model's predefined vocabulary dictionary (typically consisting of 32,000 to 100,000+ unique tokens).

3. Vector Embedding Transformation: The token IDs are passed to an Embedding Layer, converting each integer into a high-dimensional vector (a series of continuous numbers) that encodes semantic meaning for neural processing.

------
**Summary**
In Large Language Models (LLMs), text processing revolves around three core concepts:

Tokens: The fundamental unit of text the AI processes. One token equals roughly 4 characters or 0.75 English words. Words can be whole words or split into sub-word pieces.

Tokenization: The 3-step conversion process that breaks raw text into sub-words, assigns each a numerical ID from a fixed vocabulary, and translates those IDs into vector embeddings for the model to process mathematically.

Context Window: The model's working memory limit. It dictates the maximum total number of tokens (system instructions + prompt history + generated response) an LLM can evaluate at one time before older information gets truncated.

