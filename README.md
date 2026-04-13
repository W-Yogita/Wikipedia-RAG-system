# Wikipedia RAG System 📚🤖

An advanced Retrieval-Augmented Generation (RAG) application that enables interactive, AI-driven conversations with Wikipedia content. This system leverages semantic indexing to provide accurate answers based on real-time data.

## 🚀 Project Overview
This project is designed to solve the problem of LLM hallucinations by grounding responses in verified Wikipedia articles. It uses a modern RAG pipeline to retrieve, rank, and process information before generating a final response.

## 🛠️ Tech Stack
* **Language:** Python 3.10+
* **LLM Orchestration:** LangChain
* **Generative Model:** OpenAI GPT-4o / GPT-3.5-turbo
* **Embeddings:** OpenAI Text-Embedding-3-Small
* **Vector Store:** ChromaDB
* **Web Framework:** Streamlit

## 📋 Key Features
* **Dynamic Content Retrieval:** Fetches live data directly from Wikipedia.
* **Intelligent Chunking:** Processes large articles into manageable segments for better context retention.
* **Vector Search:** Uses semantic similarity to find the most relevant information.
* **Source Transparency:** Provides the context used to generate the AI response.

## ⚙️ Setup & Installation

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/W-Yogita/Wikipedia-RAG-system.git](https://github.com/W-Yogita/Wikipedia-RAG-system.git)
   cd Wikipedia-RAG-system
2. Set up Environment Variables:
Create a .env file in the root directory:

Plaintext
OPENAI_API_KEY=your_openai_api_key_here

3. Install Dependencies:

Bash
pip install -r requirements.txt

4. Run the Application:

Bash
streamlit run app.py
