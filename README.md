## 📄 **Hybrid-RAG: Combining Retrieval and Generation for Intelligent Responses**  

## 📌 About the Project  

This project implements a **hybrid Retrieval-Augmented Generation (RAG)** system that uses **BERT and GPT-2** to deliver more accurate and contextually relevant responses.  

### 🎯 **Key Features**  
✅ **Intelligent Information Retrieval:** Uses **BERT + FAISS** for fast and precise document search.  
✅ **Optimized Response Generation:** Combines retrieved information with the original query and leverages **GPT-2** for response generation.  
✅ **Efficient Vector Processing:** Stores and searches documents in a **vector index** using **FAISS**.  

---

## 🔧 Installation & Requirements  

### Dependencies  
**Libraries used in this project:**  
- `torch`
- `transformers`
- `faiss-gpu`
- `numpy`
- `scipy`
---

### Run the Notebook   
```bash
jupyter notebook hybrid-rag.ipynb
```  

---

## 🔧 **How the System Works**  

1️⃣ **Embedding:**  
   - Scientific texts and documents are converted into **embeddings**.  
2️⃣ **Indexing:**  
   - Vectors are stored in a **FAISS Index** for searchability.  
3️⃣ **Retrieval:**  
   - When a query is received, the most relevant documents are **searched and retrieved**.  
4️⃣ **Augmentation:**  
   - The original query + retrieved texts are combined.  
5️⃣ **Generation:**  
   - The **GPT-2** model uses the new input to generate a **precise and relevant response**.
   - 
---

- If you have suggestions for improving the project, please submit a **Pull Request**.  
- To report issues, please open an **Issue**.  

---  
