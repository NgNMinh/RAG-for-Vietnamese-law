RAG-based Legal Chatbot

This project implements a Retrieval-Augmented Generation (RAG) system for legal document retrieval and question answering in Vietnamese. The system loads legal documents, processes and embeds them, retrieves relevant contexts, and generates responses using a fine-tuned Vietnamese legal language model.

🚀 RAG Workflow

1️⃣ Load Documents: Import legal documents from a specified .docx file.

2️⃣ Embedding & Storage: Process and embed the text using a multilingual embedding model for efficient retrieval.

3️⃣ Context Retrieval: Fetch relevant legal contexts from stored embeddings based on user queries.

4️⃣ Response Generation: Generate answers using the fine-tuned Vietnamese legal language model.

5️⃣ (Optional) Reranking: Enhance retrieval accuracy using reranking methods.

🛠️ Usage

1️⃣ Upload Legal Documents: Ensure that the .docx file is correctly uploaded and the file path is set properly.

2️⃣ Run the System: Execute the project by running RunAll in the app_RAG file.

3️⃣ Interact with the Chatbot: Once execution is complete, a chatbot interface will appear. Simply ask a legal question, and the chatbot will process it to provide an answer.

📊 Performance Comparison

Model Performance Comparison

This chart illustrates the performance comparison between different models used in the system:
![image](https://github.com/user-attachments/assets/e5165d43-6e7b-447a-a623-3d1956f41945)


Effectiveness of RAG

The following comparison highlights the improvement in answer quality before and after applying RAG:
![image](https://github.com/user-attachments/assets/712b2975-0b1f-411d-b226-ef1b6c2760c1)


💡 Note: This system is designed for legal professionals and researchers who need quick and accurate retrieval of legal information in Vietnamese.

📩 For questions or contributions, feel free to open an issue or submit a pull request!


   


