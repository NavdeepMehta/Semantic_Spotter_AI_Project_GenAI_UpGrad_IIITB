# Semantic Spotter AI — GenAI (UpGrad × IIITB)
**Simplifying insurance document queries using Retrieval-Augmented Generation (RAG) with LlamaIndex and modern GPT models.**

[![License: MIT](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![Python](https://img.shields.io/badge/python-3.8%2B-brightgreen.svg)](https://www.python.org/)

---

## ✨ About the Project
RAG Insurance Assistant is an innovative solution designed to simplify the process of understanding and extracting information from complex insurance documents. Traditional methods of sifting through policy documents, claim guidelines, and legal jargon can be time-consuming and frustrating for users. This project eliminates these pain points by leveraging **Retrieval-Augmented Generation (RAG)** technology powered by **LlamaIndex**.

The assistant utilizes **LlamaIndex** to efficiently retrieve relevant sections of insurance documents and combines it with the natural language generation capabilities of state-of-the-art AI models like GPT-4 or Gemini. This two-step approach ensures accurate, context-aware responses to user queries, making insurance information easily accessible.

**Key Benefits**
- **Streamlined Information Access:** Ask specific questions and receive precise, concise answers instantly.
- **Enhanced Contextual Understanding:** Breaks down complex legal language into user-friendly explanations.
- **Powerful Scalability:** Handles large datasets effortlessly, suitable for personal and enterprise use.

**Example Use Cases**
- “What is covered under my health insurance policy?”
- “How can I file a claim for vehicle insurance?”

---

## 🔍 Key Features
- 🌟 **Efficient Document Retrieval:** LlamaIndex retrieves the most relevant sections quickly for precise answers.
- 🤖 **Context-Aware Responses:** Combines advanced retrievers with GPT-4 / GPT-4o / GPT-4o-mini or Gemini for grounded outputs.
- 🔄 **Vector Store Integration:** Uses **ChromaDB** for fast, scalable embeddings storage and querying.
- 📄 **Document Agnostic:** Works with PDFs, Word files, and text files.
- 🧩 **Flexible Chunking:** Customizable chunk sizes and overlaps to boost retrieval accuracy.
- 🌐 **Cloud or Local Deployment:** Run locally or deploy in your preferred cloud.
- 🔑 **Secure Access:** API keys and sensitive data handled securely.
- 📊 **Analytics-Ready (Optional):** Track query patterns to improve content and UX.
- 💬 **Conversational Interface:** Natural dialogue for policy and claims questions.
- 🚀 **Future-Ready:** Easily extendable to legal, healthcare, or other document-heavy domains.

---

## 🛠️ Tech Stack
- **Language:** Python (Jupyter Notebook)
- **Frameworks/Libraries:** Transformers, ChromaDB, PDFplumber, Llama-Index, Disk Cache
- **APIs/Models:** OpenAI’s GPT-4 / GPT-4o / GPT-4o-mini, Gemini, or other SOTA models
- **Tools:** Jupyter Notebook

---

## 🚀 Getting Started
### Prerequisites
Ensure you have the following installed:
- Python 3.8+
- Docker (optional, for containerized deployment)

### Installation
1. Clone the repo:  
   `git clone https://github.com/NavdeepMehta/Semantic_Spotter_AI_Project_GenAI_UpGrad_IIITB.git`

2. Navigate to the project directory:  
   `cd Semantic_Spotter_AI_Project_GenAI_UpGrad_IIITB`

3. Install the required dependencies:  
   `pip install -r requirements.txt`

- Please note: OpenAI API keys are required for the project to function. You can obtain them from the OpenAI website and change the same in the code. We have updated the code and added more models to make it more dynamic in V2 of the project.

4. Run the main file from Jupyter environment:  
   **"Semantic_spotter_lamaindex_Navdeep_Mehta.ipynb"**

---

## 📖 Documentation
No documentation will be made available for this project since this project only uses technologies that already have their own documentation. Please refer to the following links for more information:
- [ChromaDB](https://docs.trychroma.com/)
- [PDFplumber](https://pypi.org/project/pdfplumber/0.1.2/)
- [Sentence Transformes](https://www.sbert.net/docs/)
- [OpenAI](https://platform.openai.com/docs/)
- [Llama-Index](https://www.llamaindex.ai/)

---

## 🛠️ Challenges/Issues Faced with fixes
- **Issue #1** — Cache layer was added in ChromaDB to prevent re-embedding of the data. This was done to avoid overloading the ChromaDB server with data and to make the retrieval process more efficient.
- **Issue #2** — Cross Encoder based Reranker was added to better select the most relevant passages from the document. This was done to improve the quality of the answers to the user queries.
- **Issue #3** — Verifying the correctness of the answers given by the model was a challenge. We used GPT-4 to verify the answers provided by the model since it is a state-of-the-art model. This was done to ensure that the answers provided by the model are accurate and relevant. We also included a human feedback system to verify the correctness of the answers provided by the model. This was done to ensure that the answers provided by the model are accurate and relevant.

---

## 🌟 Future Improvements
- [ ] Add more selectable GPT models to the project (Gemini, Claude AI, Huggingface models etc).
- [ ] Add more features to the project.
- [ ] Add more selectable Vector Store to the project (Pinecone, Weaviate etc).

---

## 🛡️ License
Distributed under the MIT License. See `LICENSE` for more information.

---

## 💬 Contact
For any queries or feedback, feel free to reach out:

**Maintainer / Contributor**
- **Email**: navdeepmehta884@gmail.com  
- **GitHub**: https://github.com/NavdeepMehta  
- **LinkedIn**: https://www.linkedin.com/in/personalnavdeep/
