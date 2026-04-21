<div align="center">

<!-- Typing animation banner -->
<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=28&pause=1000&color=00D9FF&center=true&vCenter=true&width=700&lines=Hi%2C+I'm+David+Mario+%F0%9F%91%8B;AI+Engineer+%7C+Automation+Builder;Computer+Vision+Specialist;ERP+%26+Workflow+Automation+Expert" alt="Typing SVG" />

<br/>

<a href="mailto:davidmario484@gmail.com"><img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white"/></a>
<a href="https://www.linkedin.com/in/david-mario-yohanes-samosir"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
<a href="https://github.com/DavidMarioYS"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"/></a>

<br/><br/>

<img src="https://komarev.com/ghpvc/?username=DavidMarioYS&label=Profile+Views&color=00d9ff&style=flat-square" alt="Profile Views"/>

</div>

---

## 🧠 About Me

```python
class DavidMario:
    name       = "David Mario Yohanes Samosir"
    role       = "AI Engineer | ERP Automation Specialist"
    education  = "B.Sc. Computer Science — GPA 3.96/4.00"
    location   = "Indonesia 🇮🇩"
    languages  = ["Bahasa Indonesia (Native)", "English (B1)"]

    focus_areas = [
        "🤖 AI & Deep Learning",
        "⚙️  Enterprise Automation & ERP Integration",
        "👁️  Computer Vision",
        "🔗 Microservices & API Engineering",
    ]

    current_work = "Building production-scale ERP automation ecosystems"
    thesis       = "Multi-Class Semantic Segmentation for Pipeline Corrosion Detection"
    thesis_result = "BiSeNetV3: 96.12% mIoU | 97.91% Dice Score"
```

---

## 💼 Professional Experience

### ⚙️ ERP AI Specialist *(2025 – Present)*
> **Enterprise-Scale Automation Engineering**

Engineered a production-grade automation ecosystem powering **6+ major data pipelines** for complex manufacturing operations, covering raw data, BOM, Routing, Transfer Orders, and Finished Goods.

**What I built:**
- 🏗️ **3-Layer Architecture** (Controller → Service → Logic) in Python (Flask/FastAPI) — cutting data processing from hours to minutes per batch
- 🔗 **Microservices Orchestration** via n8n integrating third-party manufacturing databases (MariaDB), Google Workspace APIs (Drive, Sheets), and Microsoft Dynamics 365 Business Central via OData V4
- 🛡️ **API Reliability Engineering**: counter-based rate limiting (500 req/batch), exponential backoff, session auto-refresh, and circuit breakers for zero data loss during high-volume ERP postings
- 📊 **Automated Data Transformation** with pandas, openpyxl, xlwings processing thousands of daily production records
- 📲 **Real-Time Operational Alerts** via WhatsApp Bot API for live validation notifications

**Automation Pipelines Delivered:**

| Pipeline | Description | Stack |
|----------|-------------|-------|
| 🪟 Glass Processing Automation | End-to-end XML/Excel ingestion → Work Order generation → ERP posting | Python, Flask, n8n |
| 🎨 Accessory Color-Variant Pipeline | Automated accessory color/bin/powder data sync to ERP | Flask, Google Drive, OData |
| 🏠 Aluminum Panel Automation | Panel data monitoring → BOM/Routing generation → ERP integration | Python, pandas, n8n |
| 📦 New Item Registration Pipeline | Auto-registers new aluminum items with BOM & Routing to ERP | Flask, OData V4, openpyxl |
| 🔄 Transfer Order Automation | Full BOM-to-ERP transfer order pipeline with real-time validation | Python, MariaDB, n8n |
| 🏭 Production Order (RPO) Automation | 6-stage pipeline: Cutting → Item FG → RPO → Routing → Components | Python, Flask, BC OData |

---

### 🔬 AI Engineer – Student Researcher *(Nov 2024 – Feb 2025)*
> **Universitas Pendidikan Ganesha — VVIP-RG Research Group**

- Researched **multi-class semantic segmentation** for pipeline corrosion detection
- Compared **Mobile U-Net** vs **BiSeNetV3 (EfficientNetB1 backbone)** on 256×256 pipeline images
- BiSeNetV3 achieved **96.12% mIoU** and **97.91% Dice Score** at 0.48s/image inference
- Delivered findings as invited speaker at academic sharing sessions

---

### 🤖 AI Engineer Intern *(Aug – Dec 2024)*
> **PT Dago Engineering** · Rating: **"Sangat Baik" (Outstanding)**

- Built and benchmarked 4 segmentation models: **Mobile U-Net**, **FCN-8**, **BiSeNetV2**, **ResNet-50**
- Managed complete ML pipeline: data labeling, preprocessing, augmentation → Streamlit deployment
- Presented model metrics and progress directly to clients

---

### 🎓 ML Specialist Intern *(Feb – Jul 2024)*
> **Bangkit Academy** by Google, Tokopedia, Gojek, Traveloka · **Distinction Graduate**

- Built a **Content-Based Filtering tourism recommendation system** end-to-end
- Converted H5 models → TFLite & TensorFlow.js for cross-platform deployment
- Delivered capstone presentation in English to an international panel

---

## 🚀 Projects

<details>
<summary><b>🤖 SmartPhn — AI-Powered Smartphone Advisor (2026)</b></summary>

> `FastAPI` · `KNN` · `Machine Learning` · `Vercel` · [Live Demo ↗](https://smart-phn-syqd.vercel.app)

- Recommends from **395 smartphones** using a KNN engine with MinMaxScaler preprocessing
- Achieved **93.98% heuristic accuracy** across 90 test scenarios
- IR Metrics: Precision@5: 57.03% | MRR: 52.66% | NDCG@5: 52.73%

</details>

<details>
<summary><b>🌐 DMNet — Professional IT Network Suite (2026)</b></summary>

> `Node.js` · `FastAPI` · `Groq Llama 3.3 (70B)` · `Vercel Serverless` · [Live Demo ↗](https://dm-net-app.vercel.app)

- IPv4/IPv6 calculator, Smart Advisor, automated VLSM/FLSM subnet planner with CSV export
- AI chatbot powered by **Groq Llama 3.3 (70B)** supporting Indonesian & English
- Glassmorphism UI deployed serverless on Vercel

</details>

<details>
<summary><b>📋 Automated CV Analysis & Scoring Pipeline (2025)</b></summary>

> `n8n` · `Google Gemini Pro` · `Docker` · `Google Sheets` · `Google Drive`

- End-to-end HR screening workflow triggered by new Drive uploads
- **Weighted scoring (1–100)** with predefined criteria, auto-populating Google Sheets
- Containerized with Docker Compose for reproducible deployment

</details>

<details>
<summary><b>🍾 Computer Vision: Bottle Type Detection & Classification (2025)</b></summary>

> `YOLOv8` · `MobileNetV2` · `Streamlit` · `MLOps`

- Real-time multi-class detection (plastic, glass, spray) from video streams and live camera
- Full MLOps lifecycle: dataset labeling → augmentation → training → Streamlit deployment

</details>

<details>
<summary><b>🌏 NLLB Multilingual Translator (2025)</b></summary>

> `Python` · `Streamlit` · `Meta NLLB`

- Web-based translator using **Meta's NLLB** model, supporting Indonesian regional languages
- Real-time translation request handling with interactive frontend

</details>

---

## 🛠️ Tech Stack

<div align="center">

### AI / ML
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![Keras](https://img.shields.io/badge/Keras-D00000?style=for-the-badge&logo=keras&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white)
![YOLO](https://img.shields.io/badge/YOLOv8-00FFFF?style=for-the-badge&logo=yolo&logoColor=black)

### Automation & Backend
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)
![n8n](https://img.shields.io/badge/n8n-EA4B71?style=for-the-badge&logo=n8n&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)

### LLM & APIs
![Google Gemini](https://img.shields.io/badge/Google_Gemini-4285F4?style=for-the-badge&logo=google&logoColor=white)
![Groq](https://img.shields.io/badge/Groq_Llama-FF6600?style=for-the-badge&logoColor=white)
![Microsoft Dynamics](https://img.shields.io/badge/MS_Dynamics_365-002050?style=for-the-badge&logo=microsoft&logoColor=white)

### Data & Deployment
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

</div>

---

## 📊 GitHub Stats

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=DavidMarioYS&show_icons=true&theme=tokyonight&hide_border=true&include_all_commits=true&count_private=true" height="165" alt="GitHub Stats"/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=DavidMarioYS&layout=compact&theme=tokyonight&hide_border=true&langs_count=8" height="165" alt="Top Languages"/>
</div>

<div align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=DavidMarioYS&theme=tokyonight&hide_border=true" alt="GitHub Streak"/>
</div>

---

## 🏆 Certifications & Achievements

| Badge | Certificate |
|-------|-------------|
| 🎓 | Natural Language Processing Specialization — *deeplearning.ai / Coursera* |
| 🎓 | Advanced Computer Vision with TensorFlow — *deeplearning.ai / Coursera* |
| 🎓 | TensorFlow: Data and Deployment Specialization — *deeplearning.ai / Coursera* |
| 🎓 | Machine Learning Specialization — *deeplearning.ai / Coursera* |
| 🎓 | Google Data Analytics Professional Certificate — *Google / Coursera* |
| 🏅 | **Distinction Graduate** — Bangkit Academy (Google, Gojek, Tokopedia, Traveloka) |
| ⭐ | **"Sangat Baik" (Outstanding)** — Field Work Program, PT Dago Engineering |
| 🏆 | **Top 163** — Innovilage Social Project Program |

---

## 🎵 A Little About Me

- 🎤 Love **singing** and exploring new music
- 🏸 Badminton keeps me sharp and energized
- 🎬 Movie nights and travel are my reset buttons
- 💡 Firm believer: *automation should free humans to do what machines can't*

---

<div align="center">

### 🧠 Quote of the Day
<img src="https://quotes-github-readme.vercel.app/api?type=horizontal&theme=tokyonight" alt="Quote"/>

<br/><br/>

*"Building systems that think, automate, and scale."*

**— David Mario Yohanes Samosir**

</div>
