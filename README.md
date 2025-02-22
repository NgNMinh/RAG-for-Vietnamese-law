- INSTALLATION:

Install necessary dependencies:

!pip install --no-deps bitsandbytes accelerate xformers==0.0.29 peft trl triton
!pip install --no-deps cut_cross_entropy unsloth_zoo
!pip install sentencepiece protobuf datasets huggingface_hub hf_transfer
!pip install --no-deps unsloth
!pip install --quiet langchain_huggingface langchain-chroma langchain langchain_community datasets unstructured[local-inference] gradio

RAG Stepts:

1. Load legal documents into the system from a specified .docx file.

2. Process and embed the text using a multilingual embedding model for efficient retrieval.

3. Retrieve relevant legal contexts from the stored embeddings based on user queries.

4. Generate answers using the fine-tuned Vietnamese legal language model.

5. Optionally, apply reranking methods to enhance retrieval accuracy.

USAGE:

1. After uploading the DOCX files correctly as required (verify the correct file path), click RunAll to execute the project.

2. Once the execution is complete, a chatbot interface will appear.

3. Usage: Ask a question, and the chatbot will process it and provide an answer.
