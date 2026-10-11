<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&pause=1000&color=378ADD&width=600&lines=ML+Engineer+%7C+Data+Scientist;NLP+%7C+LLMs+%7C+RAG;Computer+Vision+%7C+Edge+AI;ML+Research+Intern+%40+MANIT+Bhopal;IIT+Ropar+AI+Certified;Currently+Sharpening+DSA+Fundamentals;Open+to+Internships+%26+Related+Roles" alt="Typing SVG" />
</a>

# Hi, I'm Labhansh Goyal

**ML Engineer & Data Scientist** — I build end-to-end intelligent systems: from raw data and model training to deployed APIs and interactive interfaces. My focus is applied ML, computer vision, NLP, LLM engineering, and deep learning.

Final-year Electrical Engineering student at MITS Gwalior (2023–2027) with a Major Certification in Artificial Intelligence from IIT Ropar (coursework: Neural Networks & LLMs, Computer Vision, NLP, Data Science, Prompt Programming). Completed an ML Research Internship at MANIT Bhopal, building real-time gesture-controlled interfaces for ISRO spacecraft environments, and authored a research paper on the work for Elsevier's *Journal of Space Safety Engineering*. Open to internships and junior roles in Data Science, ML Engineering, or AI product teams — remote and hybrid welcome.

---

## Tech Stack

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-007396?style=flat-square&logo=openjdk&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![Keras](https://img.shields.io/badge/Keras-D00000?style=flat-square&logo=keras&logoColor=white)
![HuggingFace](https://img.shields.io/badge/Hugging%20Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![ONNX](https://img.shields.io/badge/ONNX-005CED?style=flat-square&logo=onnx&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

Also working with: `Transformers (RoBERTa)` · `XGBoost` · `Prophet` · `MediaPipe` · `Reinforcement Learning (PPO)` · `Mixed Precision (AMP)` · `TextBlob` · `Google Gemini API` · `NewsAPI` · `Yahoo Finance API`

---

## Currently Learning

**Data Structures & Algorithms** — Sharpening core CS fundamentals in Java for technical interviews and to write more efficient, production-grade ML systems.
`Java` · `Arrays & Strings` · `Trees & Graphs` · `Dynamic Programming` · `Problem Solving`

---

## Experience

**ML Research Intern — Real-Time Contactless HCI for Space Missions (ISRO)**
*Maulana Azad National Institute of Technology (MANIT), Bhopal* · June 2026 – July 2026

- Developed a real-time contactless gesture recognition system for ISRO spacecraft, achieving 91.7% accuracy and a 0.90 F1-score across 11 gesture classes using a hybrid CNN-GRU architecture.
- Engineered a two-stage MediaPipe pipeline for 3D skeletal tracking, reducing input dimensionality by 14,000× and enabling 30 FPS execution on CPU-only edge hardware.
- Built an adversarial testing framework across 5 space-specific conditions, sustaining 88% accuracy under sensor noise and 78% accuracy with glove occlusion.

---

## Projects

### [DeepLab — Semantic Segmentation on VHR Satellite Imagery](https://github.com/labhanshgoyal/DeepLab-VHR-Semantic-Segmentation)
Semantic segmentation pipeline comparing four DeepLab architectures (V1, V2, V3, V3+) on the NWPU VHR-10 satellite dataset, reaching 48% mIoU across 10 object classes with a PyTorch ResNet-101 backbone. Built as a modular training framework with a CLI interface, mixed precision training (AMP), custom BCE+Dice and Focal loss functions, and ONNX export for deployment.
`PyTorch` · `DeepLab` · `ResNet-101` · `Semantic Segmentation` · `AMP` · `ONNX` · `Computer Vision`

### [Safety Alignment Classifier — Adversarially Robust Toxicity Detection](https://github.com/labhanshgoyal/Safety-Alignment-Classifier)
Toxicity classifier built by fine-tuning RoBERTa on 160K Jigsaw comments, reaching a 93% F1-score on clean data and 79% accuracy on adversarial inputs through PPO-based reinforcement learning policy correction. Includes a 6-vector adversarial perturbation engine that simulates real-world content-filter evasion tactics.
`RoBERTa` · `HuggingFace Transformers` · `PPO` · `Reinforcement Learning` · `Adversarial Robustness` · `NLP`

### [FinSights AI — Financial Analysis with LLMs, NLP & RAG](https://github.com/labhanshgoyal/FinSights-AI)
Real-time stock prediction engine built with Streamlit, combining XGBoost and Prophet on live Yahoo Finance data to forecast next-day price direction across 20+ tickers with 60–68% accuracy and 7–90 day confidence-interval horizons. Layers in an NLP sentiment pipeline processing 30+ articles per stock via NewsAPI and TextBlob, visualized through interactive Plotly dashboards. Adds RAG-powered financial Q&A using the Google Gemini LLM, grounding responses in live price data, model predictions, and sentiment scores to reduce hallucination and enable context-aware conversational analytics.
`Python` · `XGBoost` · `Prophet` · `NLP` · `RAG` · `Google Gemini API` · `NewsAPI` · `Streamlit` · `Plotly`

### [EdgeGesture — Real-Time Contactless HCI for Space Missions](https://github.com/labhanshgoyal/EdgeGesture-HCI)
Research project aligned with ISRO's focus on gesture-controlled intelligent interfaces for spacecraft environments. Architected a modular gesture-to-command pipeline achieving 91.7% accuracy and a 0.89 macro F1-score across 11 gesture classes. Designed a 12× space-specific data augmentation pipeline to train a lightweight 4MB CNN-GRU model in 25 epochs. Deployed for live, browser-based real-time inference via Streamlit and WebRTC, hosted on Hugging Face Spaces.
`MediaPipe` · `CNN-GRU` · `OpenCV` · `TensorFlow` · `Edge AI` · `Streamlit` · `WebRTC`

---

## Background

- **B.Tech Electrical Engineering** — MITS Gwalior · 2023–2027
- **Major Certification in Artificial Intelligence** — IIT Ropar · 2024–2026
  Neural Networks & LLMs · Computer Vision · NLP · Data Science Fundamentals · Prompt Programming
- **ML Research Intern** — MANIT Bhopal · June–July 2026 · Real-Time Contactless HCI for Space Missions (ISRO)
- **Publication** — *A Hybrid CNN-GRU Architecture for Real-Time Hand Gesture Recognition in Microgravity Human-Computer Interaction*, The Journal of Space Safety Engineering (Elsevier) · Aug 2026
- I build real systems, not just notebooks — end-to-end pipelines from data to deployed inference.

---

## Get in touch

- labhanshgoyal465@gmail.com
- [LinkedIn — Labhansh Goyal](https://www.linkedin.com/in/labhansh-goyal/)
- [github.com/labhanshgoyal](https://github.com/labhanshgoyal)

Always open to interesting ML problems, internship conversations, and collaboration on applied AI projects.

---

*Open to Internships · Related Roles · Data Science · ML Engineering · Computer Vision · NLP · LLMs · Edge AI*
