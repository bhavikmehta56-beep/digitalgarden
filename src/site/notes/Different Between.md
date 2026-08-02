---
{"dg-publish":true,"permalink":"/different-between/","dg-note-properties":{"permalink":"AI study"}}
---

See [[Artificial Intelligence\|Artificial Intelligence]]


**Different between Generative AI vs. Agentic AI**

| Feature           | Generative AI                                   | Agentic AI                                              |
| ----------------- | ----------------------------------------------- | ------------------------------------------------------- |
| Primary Nature    | Reactive (responds strictly to user prompts)    | Proactive (drives actions to fulfill a high-level goal) |
| Output Type       | Creates content (text, images, summaries)       | Executes complex, multi-step system workflows           |
| Human Supervision | Constant human-in-the-loop needed for each step | Operates independently within human-defined guardrails  |
| Capability        | Turns input data into isolated knowledge        | Turns knowledge into autonomous, system-wide action     |

 ------
**Different between ML vs. LLM**

|Feature|Machine Learning (ML)|Large Language Model (LLM)|
|---|---|---|
|**Definition**|A branch of AI that enables systems to learn patterns from data and make predictions or decisions.|A type of ML model trained on massive amounts of text to understand and generate human-like language.|
|**Scope**|Broad field covering many algorithms and applications.|A specialized subset of ML focused on natural language processing (NLP).|
|**Primary Purpose**|Predict, classify, detect patterns, or make decisions.|Understand, generate, summarize, translate, and answer questions in natural language.|
|**Input Data**|Structured, semi-structured, or unstructured data (numbers, images, text, sensor data, etc.).|Primarily text (can also support multimodal inputs such as images and audio in some models).|
|**Output**|Predictions, classifications, recommendations, forecasts, etc.|Human-like text, code, summaries, translations, conversations, and more.|
|**Algorithms**|Decision Trees, Random Forest, SVM, Linear Regression, Neural Networks, etc.|Transformer-based neural networks (e.g., GPT, Llama, Gemini).|
|**Training Data Size**|Can range from thousands to millions of records.|Typically trained on billions or trillions of words.|
|**Training Cost**|Usually moderate, depending on the model.|Very high due to massive datasets and compute requirements.|
|**Hardware Requirements**|CPU or GPU depending on model complexity.|Usually requires powerful GPUs/TPUs for training and often GPUs for efficient inference.|
|**Data Type**|Numeric, categorical, images, audio, text, time series, etc.|Mainly text, with some models supporting images, audio, and video.|
|**Learning Objective**|Learn patterns to make predictions or decisions.|Learn language patterns to generate coherent and context-aware responses.|
|**Common Use Cases**|Fraud detection, sales prediction, recommendation systems, image recognition, demand forecasting.|Chatbots, virtual assistants, content generation, code generation, translation, summarization.|
|**Examples**|Spam classifier, stock price prediction, customer churn prediction.|ChatGPT, Claude, Gemini, Llama, Mistral.|
|**Can Work Without Language?**|✅ Yes|❌ No, language understanding/generation is central (even multimodal LLMs include language as a core component).|
|**Relationship**|Parent field.|A specialized application of ML.|

________
**Different between LLM vs. RAG*

| Feature                                    | LLM (Large Language Model)                                            | RAG (Retrieval-Augmented Generation)                                                                                     |
| ------------------------------------------ | --------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------ |
| **Definition**                             | An AI model trained on massive datasets to generate text.             | A system that combines an LLM with a retrieval mechanism to fetch relevant information before generating a response.     |
| **Knowledge Source**                       | Uses knowledge learned during training.                               | Uses both the LLM's knowledge and external documents/databases.                                                          |
| **Access to Latest Data**                  | ❌ No (unless retrained or connected to tools).                        | ✅ Yes, retrieves the latest information from external sources.                                                           |
| **Accuracy**                               | Can produce outdated or incorrect information (hallucinations).       | More accurate because it grounds answers in retrieved documents.                                                         |
| **Hallucination Risk**                     | Higher.                                                               | Lower, since responses are based on retrieved evidence.                                                                  |
| **Training Required**                      | Requires expensive model training or fine-tuning.                     | No retraining needed; simply update the knowledge base.                                                                  |
| **Data Updates**                           | Difficult—requires retraining or fine-tuning.                         | Easy—just add or modify documents in the retrieval database.                                                             |
| **Response Generation**                    | Generates answers directly from model parameters.                     | Retrieves relevant documents first, then generates an answer using them.                                                 |
| **External Knowledge**                     | Not used by default.                                                  | Core component of the system.                                                                                            |
| **Speed**                                  | Faster (single generation step).                                      | Slightly slower due to document retrieval before generation.                                                             |
| **Cost**                                   | Lower inference cost.                                                 | Slightly higher due to retrieval infrastructure (vector database, embeddings, search).                                   |
| **Best Use Cases**                         | Chatbots, content writing, brainstorming, summarization, translation. | Enterprise search, customer support, document Q&A, legal research, medical knowledge bases, internal company assistants. |
| **Example**                                | Asking, "What is photosynthesis?"                                     | Asking, "Summarize our company's HR policy from the employee handbook."                                                  |
| **Needs Vector Database?**                 | ❌ No                                                                  | ✅ Yes (commonly uses vector databases such as FAISS, Chroma, Pinecone, or Milvus).                                       |
| **Can Answer Company-Specific Questions?** | Only if trained or fine-tuned on that data.                           | Yes, by retrieving company documents at query time.                                                                      |



