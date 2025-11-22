This project is a simple and fully functional **Retrieval-Augmented Generation (RAG)** system built using:

-  PDF document ingestion  
-  Text chunking  
-  MiniLM sentence-transformer embeddings  
-  FAISS vector similarity search  
-  Flan-T5 question answering  
-  Gradio web interface

 ## Features

- Upload multiple PDF documents  
- Extract and chunk text  
- Create embeddings using `all-MiniLM-L6-v2`  
- Build a FAISS vector index  
- Retrieve top-k relevant chunks  
- Answer questions using Flan-T5  
- Display:
  - ✔ Final answer  
  - ✔ Retrieved sources (file names) 

  

**Gradio Web App**
We just need to ask the question and click of Get Answer and the UI provides:
1.Answer displayed clearly
2.Source file names

