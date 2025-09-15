# Hi, I’m Karthick K 👋
**Aspiring AI/ML Engineer** • B.Tech in Artificial Intelligence & Machine Learning (2025)  
Building ML & DL projects — computer vision, NLP, recommendation systems, and practical AI applications.

---

## 🔭 Featured Projects

### 🚆 Automatic Train Coach Detection and Counting with YOLOv8
An **AI-powered computer vision pipeline** that automatically detects and counts train coaches and engines from side-view videos.  
Uses **YOLOv8** for object detection, **DeepSORT** for tracking, and **OpenCV** for video processing. The system also generates **per-coach clips** and **representative frames** (nose-to-tail coverage).  

**Key Features:**
- 🎯 Fine-tuned YOLOv8 on a **custom dataset (~450 annotated images)** for accurate detection  
- 🧭 **Object Tracking** using DeepSORT to avoid duplicate counts  
- 🎬 Generated **per-coach video clips** and **representative frames** for each coach  
- ✅ Validated on multiple real train-passing videos  

![Train Project Screenshot](train_screenshot.png)

**Technologies:** Python, YOLOv8, OpenCV, DeepSORT, Google Colab  

---

### 🎬 Conversational Movie Recommendation & Q&A Chatbot
An **AI-powered chatbot** combining **movie recommendations** with **conversational Q&A** for an engaging user experience.  
Built with **Python** and **Streamlit**, it integrates **LangChain memory** and the **Gemini API** for natural conversations, while using **FAISS** and **BERT embeddings** for semantic search.  

**Key Features:**
- 🎥 Fetches movie recommendations with posters from **TMDb API**  
- 🧠 Maintains context using **LangChain memory** for smooth multi-turn dialogue  
- 🔎 **Semantic Search** with FAISS + BERT embeddings to find contextually similar movies  
- 💬 Dual mode: answers normal queries with Gemini API and switches to recommendation mode based on user intent  

![Frontend Screenshot](frontend_screenshot.png)

**Technologies:** Python, Streamlit, LangChain, Gemini API, FAISS, BERT, TMDb API  

---

### 📊 Anomaly Detection
A **Streamlit app** for detecting anomalies in network data via CSV upload and processing.  

**Key Features:**
- 📈 Data preprocessing and visualization  
- ⚠️ Threshold-based anomaly detection  
- 💻 Interactive web interface with **Streamlit**  

![Anomaly Detection Screenshot 1](anomaly_screenshot1.png)
![Anomaly Detection Screenshot 2](anomaly_screenshot2.png)

**Repo:** `Anomaly-detection`  

**Technologies:** Python, PyTorch, Scikit-learn, Pandas, NumPy, Streamlit  

---

## 📫 Contact
- LinkedIn: [https://www.linkedin.com/in/karthick2434](https://www.linkedin.com/in/karthick2434)  
- Email: karthick24032004@gmail.com  

---

## 🔁 What I’m working on
- Upgrading movie recommender from TF-IDF to **BERT sentence embeddings** (sentence-transformers)  
- Adding **unit tests and CI** for key projects  
