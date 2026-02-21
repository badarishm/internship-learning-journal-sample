OpenAI API, Embeddings & Function Calling;

This session covered OpenAI API usage, embeddings, vector databases, RAG concepts, multimodal processing, and function calling with practical code examples.

Key Learnings:

1.OpenAI API & HTTP Requests:
- Made API calls using **httpx** and **curl**.
- Understood structure of a POST request:
  - URL
  - Headers
  - JSON body
- Used Chat Completion API.
- Learned about different endpoints and models (e.g., GPT-4.1 nano).
- Understood OpenAI API pricing basics.
- Set up API keys using environment variables and `.bashrc`.

2.Chatbot with History:
- Built a chatbot maintaining conversation history.
- Learned roles in chat:
  - system
  - user
  - assistant
- Understood how system prompts guide model behavior.
- Learned how LLM memory works within context limits.

3.Word & Vector Embeddings:
- Learned how words are converted into embeddings.
- Understood semantic meaning using vector representations.
- Calculated similarity using:
  - Cosine similarity
  - Distance formulas
- Used NumPy for vector operations.
- Retrieved most similar text using embedding comparison.

4.Vector Databases & RAG:
- Stored embeddings in a vector database.
- Used similarity search for retrieval.
- Applied RAG (Retrieval Augmented Generation) concept.

5.Multimodal Processing:
- Converted images to Base64.
- Converted image data to text using models.
- Used multimodal embeddings (text + image).
- Extracted product details from images.

6.Function Calling & Tools:
- Learned how function calling works in LLMs.
- Defined function schemas.
- Used tool choices to extract structured data.
- Extracted fields like:
  - Manufacturing date
  - Expiry date
- Automated structured JSON outputs from models.

What I Took Away:

- LLMs work with embeddings and semantic vectors.
- Similarity search helps retrieve meaningful information.
- APIs require proper request formatting and key management.
- Multimodal models can process both text and images.
- Function calling allows structured, automated workflows.
- Vector databases and RAG improve answer accuracy.

