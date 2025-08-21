# MediBot: AI Medical Chatbot using RAG

MediBot is an AI-powered chatbot designed for medical document interaction using Retrieval-Augmented Generation (RAG). 
The system integrates modern AI frameworks and tools to provide a modular pipeline for efficient medical query answering.

---

## 🚀 Project Layout

### Phase 1 – Setup Memory for LLM (Vector Database)
- Load raw PDF(s)
- Create chunks
- Generate vector embeddings
- Store embeddings in **FAISS**

### Phase 2 – Connect Memory with LLM
- Setup **Mistral** LLM (via HuggingFace)
- Connect LLM with FAISS
- Create RAG chain

### Phase 3 – Setup UI for the Chatbot
- Build chatbot with **Streamlit**
- Load vector store (FAISS) into cache
- Enable RAG-based query answering

---

## 🛠️ Tools & Technologies
- **LangChain** – AI framework for LLM applications  
- **HuggingFace** – ML/AI hub  
- **Mistral** – Large Language Model  
- **FAISS** – Vector database  
- **Streamlit** – Chatbot UI  
- **Python** – Programming language  
- **VS Code** – IDE  

---

## 🏗️ Technical Architecture
1. PDF ingestion → Chunking → Vector embeddings (FAISS)  
2. Query processing → RAG pipeline → Mistral LLM response  
3. Streamlit-based interactive chatbot interface  

---

## 📈 Future Improvements
- Add **authentication** in the UI  
- Enable **self-upload document functionality**  
- Support **multiple document embeddings**  
- Add **unit testing for RAG components**  

---

## 📌 Summary
- End-to-End modular chatbot using **RAG**  
- Integrated **Streamlit | LangChain | HuggingFace**  
- Handles **medical documents** efficiently  
- Ready for future extensibility and feedback  

---

## 📂 How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/Jainsanskar/Medical-AI-Chatbot.git
   cd medicalbot
   ```

2. Create and activate a virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate   # On Windows: venv\Scripts\activate
   ```

3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Run the Streamlit app:
   ```bash
   streamlit run app.py
   ```

---

## 🤝 Contribution
Feedback and contributions are welcome!  

 
