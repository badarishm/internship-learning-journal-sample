#  Week 3 – Prompt Experiments

During Week 3, I experimented with different prompt styles to improve LLM responses for retrieval, structured output, and multimodal understanding.

---

## Experiment 1 – Basic Retrieval Prompt

**Prompt:**
Answer the question using the provided context only.

Context:
{retrieved_chunks}

Question:
{user_query}

**Observation:**
- Reduced hallucination
- Responses became more grounded in retrieved data

---

## Experiment 2 – System Prompt Control

**Prompt:**
System:
You are a factual assistant. Use only retrieved information to answer.

User:
{question}

**Observation:**
- Improved response reliability
- Reduced creative but incorrect answers

---

## Experiment 3 – Top-K Retrieval Prompt

**Prompt:**
You are given the top 5 relevant documents.

Use them to answer the question concisely.

Question:
{query}

Documents:
{top_5_chunks}

**Observation:**
- Better contextual reasoning
- Helped test optimal retrieval logic

---

## Experiment 4 – Structured Output Prompt

**Prompt:**
Extract the following fields in JSON format:

- Manufacturing Date
- Expiry Date

Return only JSON.

Text:
{product_label}

**Observation:**
- Enabled automation
- Improved consistency for downstream processing

---

## Experiment 5 – Function Calling Prompt

**Prompt:**
Extract structured data and call the appropriate function.

Fields required:
- product_name
- manufacturing_date
- expiry_date

**Observation:**
- Enabled tool-based workflow
- Reduced manual parsing

---

## Experiment 6 – Multimodal Prompt

**Prompt:**
Analyze the image and extract product details.

Return:
- Product Name
- Expiry Date

**Observation:**
- Demonstrated multimodal capability
- Useful for real-world packaging analysis

---

## Experiment 7 – Chat Memory Prompt

**Prompt:**
Maintain conversation history and answer based on previous messages.

**Observation:**
- Enabled contextual continuity
- Improved chatbot interaction

---

## Experiment 8 – Anti-Hallucination Prompt

**Prompt:**
If the answer is not present in the context, say "Information not available."

**Observation:**
- Reduced false answers
- Increased trustworthiness

---

##  Experiment 9 – Hybrid RAG Prompt

**Prompt:**
Combine semantic similarity and keyword relevance to answer.

Use retrieved knowledge first.

**Observation:**
- Improved relevance
- Balanced precision and recall

---

##  Experiment 10 – Concise Answer Prompt

**Prompt:**
Answer in 2 sentences only.

**Observation:**
- Improved response clarity
- Reduced token usage

---

## Key Learnings

- Prompt structure affects accuracy.
- System prompts guide model behavior.
- Structured prompts enable automation.
- Retrieval-based prompts reduce hallucination.
- Multimodal prompts expand use cases.
