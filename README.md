<h1 align="center">Hi, I'm Hakimi 👋</h1>

<p align="center">
  <strong>AI Research Engineer | Computer Vision | Full-Stack Systems</strong>
</p>

<p align="center">
  Building <strong>end-to-end AI pipelines</strong> and <strong>production web platforms</strong> | from 6GB GPU training to AWS deployment.
</p>

### 🛠️ Tech Stack & Tools

| Category | Technologies |
|--- |--- |
| **AI / Machine Learning** | ![PyTorch](https://img.shields.io/badge/PyTorch-%23EE4C2C.svg?style=flat-square&logo=PyTorch&logoColor=white) ![OpenCV](https://img.shields.io/badge/OpenCV-%235C3EE8.svg?style=flat-square&logo=OpenCV&logoColor=white) |
| **Frontend Development** | ![React](https://img.shields.io/badge/react-%2320232a.svg?style=flat-square&logo=react&logoColor=%2361DAFB) ![Next.js](https://img.shields.io/badge/Next.js-black?style=flat-square&logo=next.js&logoColor=white) ![TailwindCSS](https://img.shields.io/badge/tailwindcss-%2338B2AC.svg?style=flat-square&logo=tailwind-css&logoColor=white) |
| **Backend Frameworks** | ![Laravel](https://img.shields.io/badge/laravel-%23FF2D20.svg?style=flat-square&logo=laravel&logoColor=white) |
| **Databases** | ![PostgreSQL](https://img.shields.io/badge/Postgres-%23316192.svg?style=flat-square&logo=postgresql&logoColor=white) ![MongoDB](https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=flat-square&logo=mongodb&logoColor=white) ![MySQL](https://img.shields.io/badge/mysql-%2300f.svg?style=flat-square&logo=mysql&logoColor=white) ![SQLite](https://img.shields.io/badge/sqlite-%2307405e.svg?style=flat-square&logo=sqlite&logoColor=white) |
| **Infrastructure & MLOps** | ![AWS](https://img.shields.io/badge/AWS-%23232F3E.svg?style=flat-square&logo=amazon-aws&logoColor=white) ![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=flat-square&logo=docker&logoColor=white) ![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black) ![Tailscale](https://img.shields.io/badge/Tailscale-992323?style=flat-square&logo=tailscale&logoColor=white) |
| **Languages** | ![Python](https://img.shields.io/badge/python-3670A0?style=flat-square&logo=python&logoColor=ffdd54) ![PHP](https://img.shields.io/badge/php-%23777BB4.svg?style=flat-square&logo=php&logoColor=white) ![JavaScript](https://img.shields.io/badge/javascript-%23F7DF1E.svg?style=flat-square&logo=javascript&logoColor=black) ![Bash](https://img.shields.io/badge/GNU%20Bash-4EAA25?style=flat-square&logo=GNU%20Bash&logoColor=white) |
---

### 👨‍💻 About Me

* 🎓 Software Engineering (Hons) | UniKL MIIT, graduating July 2026 
* 🤖 AI Research & Software Engineering Intern at CAIRO Lab, UTM
* ☁️ AWS Certified Cloud Practitioner (2026–2029)
* 🏠 Self-hosted homelab: Docker, Tailscale, Ubuntu | Glances, Dashy, filebrowser,Minecraft
* 📄 First-author research paper on domain-gap-bridging for wood microscopic imagerestoration
* 🔬 Passionate about Machine Learning, Computer Vision, MLOps, optimizing on constrained hardware, and cloud-deployed AI systems

---

### 🚀 Featured Projects

#### 🤖 AI Wood Image Restoration & Recognition Suite
> 99.85% species classification accuracy across 35 Malaysian hardwoods, trained 5 restoration architectures on a 6GB consumer GPU.

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![Qt](https://img.shields.io/badge/PyQt6-41CD52?style=flat-square&logo=qt&logoColor=white) ![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)

* Acquired 6,842 paired images (clear/blur) across 35 species via multi-threadedPyQt6 camera pipeline at ≥30 FPS
* Benchmarked 5 architectures (SwinIR, Real-ESRGAN, VDSR, SRCNN, Simple CNN) —SwinIR selected at PSNR 21.20 dB (Wiener baseline: 3.56 dB)
* Overcame 3–4× VRAM shortfall on 6GB GPU via gradient accumulation, dynamicresolution scaling, and a 2GB RAM cache
* Domain gap discovery: physics-based training halves the synthetic-to-real gapfrom −7.65 dB to −3.84 dB proven by ablation study
* First-author paper documenting findings with 4.2 GB of reproducible artifacts
* 🔗 [GitHub Repo](https://github.com/hakimisch/ai-wood-image-restoration)

---

#### 🗃 CAIRO Inventory Management System
> Digitizing research equipment across 2 campuses - 34 government compliance forms, automated PDF generation, and OCR batch import.

![Laravel](https://img.shields.io/badge/Laravel-FF2D20?style=flat-square&logo=laravel&logoColor=white) ![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black) ![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazon-aws&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=flat-square&logo=postgresql&logoColor=white)

*  Deployed on AWS Elastic Beanstalk + RDS + S3 | 38 controllers, ~130 routes, 58React pages
* Built 1,201-line OCR engine batch-importing 51 PO items + 59 DO items fromsupplier PDFs, bypassing manual data entry
* All 34 KEW.PA government forms (PA-1 → PA-32) with one-click PDF generation viaChromium
* Three user roles, admin dashboards with Chart.js, activity audit logging
* 🔗 [GitHub Repo](https://github.com/hakimisch/cairo-inventory)

---

#### 🧠 Homelab Inference Cluster
> Distributed AI inference stack — vLLM, Ollama, Prometheus/Grafana, Streamlit — Dockerized across WSL (RTX 4070) + homelab, linked via Tailscale.
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white) ![vLLM](https://img.shields.io/badge/vLLM-8B5CF6?style=flat-square&logo=python&logoColor=white)
* Twin-node design: **WSL compute (RTX 4070 12 GB)** + **homelab services** — 10 Docker containers, zero public ports
* Dual engines: **vLLM** (Qwen3-8B-AWQ) + **Ollama** (Gemma 4 12B, LFM2.5-8B MoE at ~170 tok/s)
* Full observability: DCGM → Prometheus → Grafana (GPU temp, VRAM, tok/s, power)
* Streamlit control panel: live metrics, benchmark runner → MLflow, fine‑tuning launcher
* **Serves as the infrastructure for:**
  * 🧪 [Engram Experiment](https://github.com/hakimisch/pawaaaa-s-engram-experiment) — DeepSeek's conditional memory replicated on consumer hardware
  * ⏳ *More experiments & benchmarks coming soon*
* 🔗 [GitHub Repo](https://github.com/hakimisch/pawaaaa-s-inference-cluster)

---

#### 🎨 Artspace – AI-Enhanced Digital Artist Portfolio
> Full-stack Next.js platform supporting secure e-commerce integrations and generative AI features.

![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=next.js&logoColor=white) ![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white) ![Gemini](https://img.shields.io/badge/Gemini_AI-8E75C2?style=flat-square&logo=google-gemini&logoColor=white) ![PayPal](https://img.shields.io/badge/PayPal-003087?style=flat-square&logo=paypal&logoColor=white)

* 43 API routes · 11 MongoDB models · 39 frontend pages across admin, artist, andcustomer dashboards
* Integrated Google Gemini 2.5 Flash AI chatbot with admin-configurable prompts,intent detection, and daily analytics
* PayPal e-commerce with order creation, capture, and fulfillment tracking
* Live at ai-artspace.vercel.app — solo project, 34 commits
* 🔗 [Live Site](https://ai-artspace.vercel.app) | [GitHub Repo](https://github.com/hakimisch/AI-Enhanced-Portfolio)

---

### 📝 Publications
"Bridging the Optical Domain Gap: A Physics-Based Deep Learning Framework forMacroscopic Wood Image Restoration" - First author, CAIRO Lab UTM, 2026

> Proves that physics-based degradation simulation reduces the synthetic-to-realdomain gap by 50% (7.65 dB → 3.84 dB) for wood microscopic image restoration.Includes 14,600-word thesis draft with 4.2 GB of reproducible artifacts.

---

### 📊 GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=hakimisch&show_icons=true&theme=radical" height="170" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=hakimisch&layout=compact&theme=radical" height="170" />
</p>

---

### 📫 Connect

**LinkedIn:** [https://www.linkedin.com/in/muhammad-hafiz-hakimi-925977269](https://www.linkedin.com/in/muhammad-hafiz-hakimi-925977269) 
**GitHub:** [https://github.com/hakimisch](https://github.com/hakimisch) 
