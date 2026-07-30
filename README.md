# Hi there 👋 I'm Adithya  

🎓 Student @ Amrita Vishwa Vidyapeetham • Pursuing AI  
🤖 Enthusiastic about **AI, Generative AI, LLMs, RAG, ML/DL, Web Development**  
🚀 Actively building projects and aiming for **AI / SDE roles**  

---

## 🌟 Featured Projects  

### [MiniPat-LLM](https://github.com/The-Adi-005/MiniPat---LLM)  
🧠 A **Retrieval-Augmented Generation (RAG)** based patent evaluation system integrating **LLMs** for semantic understanding and document comparison.  
### Simplified Pipeline View

```mermaid
flowchart LR
    subgraph INPUT["Input"]
        A["📄 Patent PDF"]
    end

    subgraph PROCESS["Processing"]
        B["Text + OCR<br/>Tables<br/>Images"] --> C["Chunking<br/>Captioning"]
    end

    subgraph STORE["Storage"]
        D[("ChromaDB<br/>+ BGE-M3")]
    end

    subgraph RETRIEVE["Retrieval"]
        E["Semantic Search<br/>+ Re-ranking"]
    end

    subgraph GENERATE["Generation"]
        F["Gemini / Qwen<br/>LLM"]
    end

    subgraph OUTPUT["Output"]
        G["📝 Summary"]
        H["📊 Scores"]
    end

    A --> B --> C --> D
    D --> E --> F --> G --> H

    classDef default fill:#2d2d2d,stroke:#555,color:#e0e0e0,rx:8
    classDef io fill:#1e3a5f,stroke:#4a90d9,color:#fff,rx:12
    class A,G,H io
```

### [Video_Captioning_VisionEncoder-Decoder](https://github.com/THE-Adi-005/Video_Captioning_VisionEncoder-Decoder)  


### [Meat_Quality_Grading](https://github.com/The-Adi-005/Meat_Quality_Grading)  
🥩 Deep Learning-based Meat Freshness Classification with Explainable AI
## 🏗️ Architecture & Pipeline

```
┌─────────────────────────────────────────────────────────────┐
│                    MASTER EXPERIMENT RUNNER                  │
├─────────────────────────────────────────────────────────────┤
│                                                             │
│   ┌─────────────┐  ┌─────────────┐  ┌──────────────────┐   │
│   │  ConvNet24  │  │  ResNet18   │  │   MobileNetV2    │   │
│   │  (Custom)   │  │ (Pre-built) │  │   (Pre-built)    │   │
│   └──────┬──────┘  └──────┬──────┘  └────────┬─────────┘   │
│          │                │                   │             │
│   ┌──────┴──────────────┬─┴─────────────┬─────┘             │
│   │      Optimizers     │               │                   │
│   │  Adam | SGDM | RMS  │               │                   │
│   └──────┬──────────────┘               │                   │
│          │                              │                   │
│   ┌──────▼──────┐                ┌──────▼──────┐            │
│   │  Individual │                │   Ensemble  │            │
│   │  Evaluation │                │   (Avg Prob)│            │
│   └──────┬──────┘                └──────┬──────┘            │
│          │                              │                   │
│   ┌──────▼──────────────────────────────▼──────┐            │
│   │         OUTPUTS PER CONFIGURATION          │            │
│   │  • Confusion Matrix (PNG)                  │            │
│   │  • Metrics CSV (Acc, Prec, Rec, F1)        │            │
│   │  • Grad-CAM Heatmaps (5 samples)           │            │
│   └────────────────────────────────────────────┘            │
└─────────────────────────────────────────────────────────────┘
```

---

## 🛠️ Tech Stack  

**Languages & Core**  
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)  
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)  
![SQL](https://img.shields.io/badge/SQL-336791?style=for-the-badge&logo=postgresql&logoColor=white)  

**Frameworks & Libraries**  
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)  
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)  
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)  
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)  
![Express.js](https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white)  

**Other Skills**  
🔹 DSA • API Development • GitHub Actions  

---

## 📜 Certifications  

<p align="center">
  <a href="https://github.com/THE-Adi-005/The-Adi-005/blob/main/assets/Coursera%20EA4JVM09Q5OZ.pdf"><img src="https://github.com/THE-Adi-005/The-Adi-005/blob/main/assets/Coursera%20EA4JVM09Q5OZ.pdf" width="150"></a>
  <!-- <a href="assets/cert2.png"><img src="assets/cert2.png" width="150"></a>
  <a href="assets/cert3.png"><img src="assets/cert3.png" width="150"></a> -->
</p>  

---

## 📊 GitHub Stats  

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=The-Adi-005&show_icons=true&theme=tokyonight" height="160">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=The-Adi-005&layout=compact&theme=tokyonight" height="160">
</p>  

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com?user=The-Adi-005&theme=tokyonight" height="160">
</p>  

---

## 📫 Connect with me  

[![Email](https://img.shields.io/badge/Email-adithya%40email.com-green?style=for-the-badge&logo=gmail)](mailto:adithyakrs2408@email.com)  
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Profile-blue?style=for-the-badge&logo=linkedin)](https://linkedin.com/in/adithya-r-63b216291)  

---

✨ *Thanks for stopping by! Check out my pinned projects below for more details.*  
