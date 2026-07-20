<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&pause=1000&color=378ADD&width=600&lines=ML+Engineer+%7C+Data+Scientist;NLP+%7C+LLMs+%7C+RAG;ISRO+Research+Intern+%40+MANIT+Bhopal;IIT+Ropar+AI+Certified;Currently+Sharpening+DSA+Fundamentals;Open+to+Internships+%26+Related+Roles" alt="Typing SVG" />
</a>

# Hi, I'm Labhansh Goyal

**ML Engineer & Data Scientist** — I build end-to-end intelligent systems: from raw data and model training to deployed APIs and interactive interfaces. My focus is applied ML, NLP, LLM engineering, and deep learning.

Final-year Electrical Engineering student at MITS Gwalior (2023–2027) with a Major Certification in Artificial Intelligence from IIT Ropar (coursework: Neural Networks & LLMs, Computer Vision, NLP, Data Science, Prompt Programming). Completed an ML Research Internship at MANIT Bhopal, building real-time gesture-controlled interfaces for ISRO spacecraft environments. Open to internships and junior roles in Data Science, ML Engineering, or AI product teams — remote and hybrid welcome.

---

## Tech Stack

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-007396?style=flat-square&logo=openjdk&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![Keras](https://img.shields.io/badge/Keras-D00000?style=flat-square&logo=keras&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)
![HuggingFace](https://img.shields.io/badge/Hugging%20Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

Also working with: `XGBoost` · `Prophet` · `Librosa` · `MediaPipe` · `TextBlob` · `Gradio` · `Google Gemini API` · `NewsAPI` · `Yahoo Finance API`

---

## Currently Learning

**Data Structures & Algorithms** — Sharpening core CS fundamentals in Java for technical interviews and to write more efficient, production-grade ML systems.  
`Java` · `Arrays & Strings` · `Trees & Graphs` · `Dynamic Programming` · `Problem Solving`

---

## Experience

**ML Research Intern — Real-Time Contactless HCI for Space Missions (ISRO)**
*Maulana Azad National Institute of Technology (MANIT), Bhopal* · June 2026

- Developed a real-time contactless gesture recognition system for ISRO spacecraft, achieving 91.7% accuracy and a 0.90 F1-score across 11 gesture classes using a hybrid CNN-GRU architecture.
- Engineered a two-stage MediaPipe pipeline for 3D skeletal tracking, reducing input dimensionality by 14,000× and enabling 30 FPS execution on CPU-only edge hardware.
- Built an adversarial testing framework across 5 space-specific conditions, sustaining 88% accuracy under sensor noise and 78% accuracy with glove occlusion.

---

## Projects

### [EdgeGesture — Real-Time Contactless HCI for Space Missions](https://github.com/labhanshgoyal/EdgeGesture-HCI)
Research project aligned with ISRO's focus on gesture-controlled intelligent interfaces for spacecraft environments. Architected a modular gesture-to-command pipeline achieving 91.7% accuracy and a 0.89 macro F1-score across 11 gesture classes. Designed a 12× space-specific data augmentation pipeline to train a lightweight 4MB CNN-GRU model in 25 epochs. Deployed for live, browser-based real-time inference via Streamlit and WebRTC, hosted on Hugging Face Spaces.
`MediaPipe` · `CNN-GRU` · `OpenCV` · `TensorFlow` · `Edge AI` · `Streamlit` · `WebRTC`

### [FinSights AI — Financial Analysis with LLMs, NLP & RAG](https://github.com/labhanshgoyal/FinSights-AI)
Real-time stock prediction engine built with Streamlit, combining XGBoost and Prophet on live Yahoo Finance data to forecast next-day price direction across 20+ tickers with 60–68% accuracy and 7–90 day confidence-interval horizons. Layers in an NLP sentiment pipeline processing 30+ articles per stock via NewsAPI and TextBlob, visualized through interactive Plotly dashboards. Adds RAG-powered financial Q&A using the Google Gemini LLM, grounding responses in live price data, model predictions, and sentiment scores to reduce hallucination and enable context-aware conversational analytics.
`Python` · `XGBoost` · `Prophet` · `NLP` · `RAG` · `Google Gemini API` · `NewsAPI` · `Streamlit` · `Plotly`

### [Speech Emotion Recognition](https://github.com/labhanshgoyal/CodeAlpha)
CNN-based deep learning system classifying 8 emotions from 1,440 RAVDESS audio samples, benchmarking 6 ML classifiers to reach 67% accuracy. Engineered 180-dimensional feature vectors (MFCC, Chroma, Mel-Spectrogram) using Librosa with StandardScaler normalization. Deployed as a real-time Gradio web app, achieving per-class precision up to 74%.
`TensorFlow` · `CNN` · `Librosa` · `MFCC` · `RAVDESS` · `Gradio` · `Audio ML`

### [Loan Approval Prediction Model](https://github.com/labhanshgoyal/Loan-Approval-Model)
End-to-end binary classification pipeline benchmarking Logistic Regression, Random Forest, and XGBoost across a multi-feature applicant dataset. XGBoost yielded the highest predictive performance. Full preprocessing pipeline: null imputation, ordinal and one-hot encoding, stratified train/test splitting. Evaluated across Accuracy, Precision, Recall, F1-Score, and ROC-AUC.
`Python` · `XGBoost` · `Random Forest` · `Logistic Regression` · `Scikit-learn` · `ROC-AUC`

### [ParkRoute AI — Route Optimisation with A\*, Greedy & Heuristic Algorithms](https://github.com/labhanshgoyal/ParkRoute-AI)
Priority-based route optimisation engine combining A* search and a Greedy heuristic hybrid, guaranteeing shortest-path discovery on weighted graphs of 300+ nodes. Custom admissible heuristic ensures optimality while reducing unnecessary node expansions versus exhaustive search. React frontend with Leaflet/Map API renders routes interactively on a real-world geographic canvas with dynamic re-routing on node selection.
`Python` · `A* Search` · `Graph Algorithms` · `React` · `Leaflet` · `Heuristic Design`

---

## Background

- **B.Tech Electrical Engineering** — MITS Gwalior · 2023–2027
- **Major Certification in Artificial Intelligence** — IIT Ropar · 2024–2025
  Neural Networks & LLMs · Computer Vision · NLP · Data Science Fundamentals · Prompt Programming
- **ML Research Intern** — MANIT Bhopal · June 2026 · Real-Time Contactless HCI for Space Missions (ISRO)
- I build real systems, not just notebooks — end-to-end pipelines from data to deployed inference.

---

## Get in touch

- labhanshgoyal465@gmail.com
- [LinkedIn — Labhansh Goyal](https://www.linkedin.com/in/labhansh-goyal/)
- [github.com/labhanshgoyal](https://github.com/labhanshgoyal)

Always open to interesting ML problems, internship conversations, and collaboration on applied AI projects.

---

*Open to Internships · Related Roles · Data Science · ML Engineering · NLP · LLMs · Audio ML · Edge AI*
