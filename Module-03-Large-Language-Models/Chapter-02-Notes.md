Embeddings, Vector DB & Hybrid RAG – Project 1:

This session focused on embeddings, vector databases, hybrid RAG, and building a similarity-based question answering system.

Key Learnings:

1.Embeddings & Similarity;
- Learned how text and images are converted into **vector embeddings**.
- Used similarity measures like:
  - Cosine similarity
  - Dot product
  - Vector norm
- Discussed cost-effective embedding models like **Sentence Transformers** and OpenAI models.

2.Multimodal Embeddings:
- Introduction to multimodal embeddings (text + image).
- Explored tools like Nomic AI.
- Used API keys and JSON format for model interaction.

3.Vector Databases:
- Stored embeddings in structured format.
- Understood how similarity search works in vector DBs.
- Used a `chunks.json` file containing:
  - ID
  - Source
  - Text
  - Embeddings

4.Chunking:
- Split large text into smaller chunks.
- Learned importance of tokens and context limits.
- Chunking improves retrieval performance.

5.Hybrid RAG:
- Combined embedding similarity with retrieval techniques.
- Retrieved top-5 most relevant chunks using embeddings.

6.Implementation Details:
- Used HTTPX for API requests.
- Used NumPy for similarity calculations.
- Handled environment variables using `.bashrc`.
- Managed API keys securely.
- Used async programming and timeout handling.
- Ensured JSON-safe responses.

7.ask_question.py:
- Built a script to:
  - Generate embedding for query
  - Compare with stored embeddings
  - Return top-5 most relevant results

What I Took Away:

- Embeddings convert data into vectors for similarity search.
- Vector databases enable fast semantic retrieval.
- Chunking is important for large documents.
- Hybrid RAG improves answer quality.
- Secure API handling and async requests are essential for real-world projects.

