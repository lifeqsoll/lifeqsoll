<div align="center">
  <img src="https://i.giphy.com/PZrjGkr334fXa.webp" width="100%" style="height: auto; border-radius: 8px;" alt="Header Banner"/>
  <br/><br/>
  <a href="https://github.com/lifeqsoll">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=24&pause=1000&color=58A6FF&center=true&vCenter=true&width=600&lines=Hi!+I'm+lifeqsoll;AI+%26+ML+Developer;Deep+Learning+%7C+Computer+Vision" alt="Typing SVG" />
  </a>
</div>

<br/>

### About & Experience

* **Education:** High school student focused on AI development.
* **Focus:** Deep learning, computer vision architectures, and multimodal models (CLIP).
* **Achievements:** **AI Challenge** — Participant in the Main Stage of the international youth AI competition.

---

### Featured projects

#### 1. SysSpectogram — host defense as computer vision

**[SysSpectogram](https://github.com/lifeqsoll/SysSpectogram)** is a Linux / VPS defense utility that treats host telemetry as images.

It samples CPU, memory, network, disk, and **GPU** metrics every second, builds 60-second windows into spectrogram-like matrices, and scores them with a **CNN (computer vision)** plus **Isolation Forest (classical ML)** ensemble — useful for behavioral anomalies such as **CPU / GPU crypto-miners**, resource abuse, and unusual host load. Around that core it adds perimeter / egress watching, OSINT on the attacker IP (nmap, DNS, certificate logs), and a Telegram / web control plane for alerts and SOAR-lite responses (ban, recon, kill — with dry-run). In v1.0 it also ships a **Tauri 2 + Svelte** Control Center desktop app, a polkit-gated root helper, a Rust integrity agent with **Aya eBPF** probes (`execve`, `openat`, module load, `kill`, `setuid`), and an incident engine with ATT&CK mapping and HTML reports.

![Version](https://img.shields.io/badge/Version-v1.0.0-2EA44F?style=flat-square)
[![Repo](https://img.shields.io/badge/GitHub-SysSpectogram-181717?style=flat-square&logo=github)](https://github.com/lifeqsoll/SysSpectogram)
[![Demo](https://img.shields.io/badge/Live_demo-Pages-0588C6?style=flat-square)](https://lifeqsoll.github.io/SysSpectogram/demo/)
[![Site](https://img.shields.io/badge/Website-bio-0B3A66?style=flat-square)](https://lifeqsoll.github.io/bio/)

#### 2. Gavel AI — layered AI-vs-real image signals

**[Gavel AI](https://github.com/lifeqsoll/gavel-ai)** is an **Apache-2.0** computer-vision prototype that looks for *signs* of AI image generation — not a courtroom “this is fake” claim, but a layered signal you can inspect.

**L0** is a frozen **OpenCLIP ViT-L/14** backbone with a calibrated linear probe (`generated` / `uncertain` / `real`). Around it sit local layers: **anatomy** (MediaPipe face / pose / hands map + strict 2D hand warnings), **artifacts** (flat-region residual kurtosis as a soft cue), **geometry** (LSD + vanishing-point consistency), and a physics stub. **Fusion A** combines them: L0 or a hard layer vote can raise a generation signal; soft artifacts cannot overturn a strong L0=`real`; a clean face-free hand close-up can veto a known L0 false positive on stock gym hands. Wide diptychs are scored on left/right tiles. Ships a **Gradio** UI, typed `EvidenceProtocol` JSON, OpenCV overlays, and training / eval tooling for the probe.

![License](https://img.shields.io/badge/License-Apache_2.0-blue?style=flat-square)
[![Repo](https://img.shields.io/badge/GitHub-gavel--ai-181717?style=flat-square&logo=github)](https://github.com/lifeqsoll/gavel-ai)
![Stack](https://img.shields.io/badge/CLIP_+_OpenCV_+_Gradio-111827?style=flat-square)

---

### Tech Stack

**Languages**
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-003B57?style=flat-square&logo=sqlite&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)

**Machine Learning & CV**
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![ONNX](https://img.shields.io/badge/ONNX-005CED?style=flat-square&logo=onnx&logoColor=white)
![CLIP](https://img.shields.io/badge/OpenCLIP_/_CLIP-7C3AED?style=flat-square)
![MediaPipe](https://img.shields.io/badge/MediaPipe-009688?style=flat-square&logo=google&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![HuggingFace](https://img.shields.io/badge/Hugging_Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black)

**Tools, UI & OS**
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Gradio](https://img.shields.io/badge/Gradio-F97316?style=flat-square)
![Svelte](https://img.shields.io/badge/Svelte-FF3E00?style=flat-square&logo=svelte&logoColor=white)
![Tauri](https://img.shields.io/badge/Tauri-24C8DB?style=flat-square&logo=tauri&logoColor=white)
![eBPF](https://img.shields.io/badge/eBPF_Aya-E95420?style=flat-square&logo=linux&logoColor=white)
![Pydantic](https://img.shields.io/badge/Pydantic-E92063?style=flat-square)

---

### GitHub languages

![Top languages](https://github-readme-stats.vercel.app/api/top-langs/?username=lifeqsoll&layout=compact&hide_border=true&langs_count=8&theme=transparent)

---

### Contact

[![Telegram](https://img.shields.io/badge/Telegram-26A5E4?style=flat-square&logo=telegram&logoColor=white)](https://t.me/emosensei)
[![X](https://img.shields.io/badge/X-000000?style=flat-square&logo=x&logoColor=white)](https://x.com/lifeqsoll)
[![Email](https://img.shields.io/badge/Gmail-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:lifeqsoll@gmail.com)
