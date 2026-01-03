# TaeYoung Jo (Lucas Jo)

I-Park Apt. 102-701, MokDong-ro 230, YangChun-gu, Seoul 07993, Korea  
+82-10-8228-3458 | [jty016@gmail.com](mailto:jty016@gmail.com)  
[LinkedIn](https://www.linkedin.com/in/lucasjo-2016/) | [GitHub](https://github.com/goodatlas)

---

## Professional Summary

**Bridging AI Agents with Telecommunication Infrastructure & Global R&D Impact.**  
A visionary technology leader and R&D expert with 10+ years of experience in speech recognition (ASR), large-scale machine learning systems, and conversational AI. As the **CTO of Atlas Labs** (and Board Director at the US parent company, **Atlasguide**), I specialize in orchestrating complex AI, VoIP, and cloud-native infrastructures, turning high-level research into scalable, market-leading products. Beyond my executive role, I lead high-impact AI initiatives for a global US-based non-profit organization (JW.org), pioneering **In-Context Learning (ICL)** for low-resource languages and architecting high-performance serverless audio processing engines. I am driven by a passion for advancing ASR technology, a journey highlighted by leading the **Zeroth Project**, which established the official Korean ASR recipe in the global **Kaldi** repository.

---

## Skills

*   **Conversational AI & Agents**: Pipecat, LangGraph, MCP (Model Context Protocol), RAG, LLM Orchestration, Real-time Voice Agents
*   **ASR & Speech AI**: Meta Omni ASR (7B ZS), Few-shot Learning (ICL), Whisper (Fine-tuning), Kaldi (Zeroth Project), Wav2Vec 2.0, ONNX Optimization
*   **Audio Engineering**: Noise Suppression (Resemble Enhance), Audio Effects (FFmpeg, NumPy-based DSP), OpenVoice, Serverless Audio APIs
*   **VoIP & Infrastructure**: Asterisk (ARI), Kamailio, SIP/WebRTC (Janus), AWS (EKS, Lambda Layer Optimization), S3-native Training, WebDataset, ArgoCD (GitOps), Terraform (IaC), RunPod/GPU Automation
*   **Leadership & Strategy**: CTO Leadership, Startup Co-founding, R&D Management, Global Technical Advisory, Board Directorship

---

## Professional Experience

### **Atlas Labs** | *Jan 2017 – Present*

#### **CTO / Head of Tech** (*Jan 2023 – Present*)
*   **Executive Leadership**: Serving as the CTO and **Board Director** at the US parent company, **Atlasguide**. Driving technical strategy and long-term R&D roadmaps for AI-driven communication products.
*   **Strategic AI-Telephony Orchestration**
    *   **Agent-VoIP Integration**: Architected a seamless bridge between LLM agents and VoIP stacks, treating the telephony layer as a programmable "communication tool." This allows AI to handle real-time, low-latency phone interactions for complex business workflows.
    *   **Project Leah (AI Agent System)**: Directed the R&D of a bidirectional voice agent system. Deployed RAG-enabled agents for inbound reception and autonomous outbound booking with real-time language detection.
    *   Built real-time voice agents using **Pipecat** and orchestrated multi-step tasks using **LangGraph** and **MCP**.
*   **Engineering Excellence & Strategic Infrastructure**
    *   **Cloud-Native GitOps & Monorepo**: Designed a high-velocity delivery pipeline for 10+ microservices using a **Monorepo**, **ArgoCD**, and **GitHub Actions**.
    *   **IaC-Driven Resilience**: Established a robust **Terraform** foundation enabling **Zero-Downtime Cluster Switching**, ensuring 99.9% availability and seamless EKS migrations.
    *   **Operational Efficiency (DevEx)**: Automated 90% of infrastructure management, effectively **eliminating the need for a 2-person DevOps team** while improving productivity via **Tailscale-based** local-to-cloud debugging.
*   **Whisper-based STT Model Optimization**
    *   Fine-tuned Whisper-large v3 using thousands of hours of real-world call logs. Built a high-performance gRPC inference server using **Nvidia Triton** and **TensorRT-LLM**.

#### **VoIP Infra Team Leader** (*Jan 2020 – Dec 2022*)
*   **Switch App Success & Advanced DevOps Implementation**
    *   Built and launched the Switch app (1M+ users, 10,000+ paid subscribers) and architected a high-availability STT system processing 15,000+ hours of calls monthly.
    *   **Modern CI/CD & GitOps**: Established a robust CI/CD pipeline using a **Monorepo** structure. Services were containerized via **GitHub Actions** and deployed using **Helm** and **ArgoCD**.
    *   **Infrastructure as Code (IaC)**: Utilized **Terraform** to automate AWS EKS cluster management and version upgrades.
*   **Wav2Vec STT Implementation**
    *   Enhanced call-domain accuracy for Korean and Japanese (75% to 89% CER) using unsupervised training and fine-tuning with Meta's Wav2Vec.

#### **ML Team Leader** (*Jan 2017 – Dec 2019*)
*   **Zeroth Project: Pioneering Korean Open-Source ASR**
    *   **Kaldi Official Recipe**: Co-developed the [Zeroth Project](https://github.com/goodatlas/zeroth), establishing the first [official Korean recipe](https://github.com/kaldi-asr/kaldi/tree/master/egs/zeroth_korean/s5) in the **Kaldi** repository.
    *   **Collaborative R&D**: Successfully completed the project in collaboration with [Wonkyum Lee](https://www.linkedin.com/in/wonkyumlee/), where I led the **Language Model (LM)** development (text normalization, morpheme analysis, pronunciation rules), while Wonkyum led the Acoustic Model (AM) training.
    *   **Commercialization**: Developed a C++ multithreaded Kaldi decoder for real-time commercial use, bridging the gap between research and production.
*   **LSTM-CRF Korean Spacing**: Developed a DNN-based spacing correction system for ASR post-processing (98% Precision/Recall).

---

## Public Speaking & Technical Education

*   **Hanyang University (ASML Lab)** | *Invited Speaker*
    *   **"Kaldi based ASR system"** (Aug 2019): Conducted a technical seminar on building production-grade ASR systems using Kaldi for the Audio, Speech and Machine Learning Lab. [[Link]](https://asmllab.hanyang.ac.kr/kor/page/bbs_view.php?idx=892&search_item=all&search_order=%EC%A1%B0%ED%83%9C%EC%98%81&code=labnews)
    *   **"Data-driven Way of Korean LM Design"** (Feb 2018): Presented methodologies for optimizing Korean Language Models (LM) using data-driven approaches. [[Link]](https://asmllab.hanyang.ac.kr/kor/page/bbs_view.php?idx=723&search_item=all&search_order=%EC%A1%B0%ED%83%9C%EC%98%81&code=labnews)
*   **FastCampus** | *Lead Instructor & Subject Matter Expert*
    *   Developed and led two consecutive intensive professional courses (30 hours each, 10 sessions x 3 hours) on **Deep Learning-based Speech Recognition** and **Kaldi System Implementation**.
    *   Featured in a technical interview regarding the impact of the **Zeroth Project** on the open-source Korean ASR community. [[Interview Article]](https://blog.naver.com/fastcampus/221181060609)
*   **K-Mobile Academy** | *Invited Instructor*
    *   **"Understanding Speech Recognition & Kaldi System Implementation"**: Led a specialized 1-day intensive workshop for industry professionals. [[Link]](https://www.kmobile.co.kr/shop/academy/%EC%9D%8C%EC%84%B1%EC%9D%B8%EC%8B%9D-%EA%B8%B0%EC%88%A0%EC%9D%98-%EC%9D%B4%ED%95%B4-%EB%B0%8F-%EC%9D%8C%EC%84%B1%EC%9D%B8%EC%8B%9D-%EC%8B%9C%EC%8A%A4%ED%85%9Ckaldi-%EA%B5%AC%ED%98%84-1day-%EC%9B%8C/?ckattempt=1)

---

### **Strategic Advisory & Global R&D (Social Impact)**

### **JW.org (WHQ MEMPS)** | *Jan 2024 – Present*
*Collaborating with the US-based World Headquarters (WHQ) to solve high-complexity language challenges for global non-profit initiatives.*

#### **Micro Team Lead, AI Services** (*Jul 2025 – Present*)
*   **Meta Omni ASR Breakthrough**: Led the adoption of **Meta’s Omnilingual ASR (7B ZS)**, leveraging **In-Context Learning (ICL)** to achieve a **30-35% CER improvement** in low-resource languages (e.g., Maya, Mixtec).
*   **Scalable Data Pipeline**: Implemented a modern **WebDataset** integration for streamed access to massive audio datasets directly from **AWS S3**, enabling remote, high-efficiency training.
*   **R&D Environment Automation**: Automated research environment bootstrapping using **RunPod (GPU/CPU)** and **Azure DevOps (ADO)**, reducing setup time to minutes.
*   **Multi-GPU Training**: Developed and validated full-scale multi-GPU fine-tuning scripts for Whisper architecture across 18+ languages.

#### **AI / Audio Engineer** (*Jan 2024 – Jun 2025*)
*   **Serverless Audio Engine**: Architected a high-performance AWS Lambda-based API for real-time audio enhancement.
    *   **Layer Optimization**: Minimized package size by re-implementing **SciPy** dependencies using **NumPy** and optimizing **FFmpeg** wrappers for serverless execution.
    *   **Noise Suppression & Effects**: Integrated **Resemble Enhance** and developed 15+ environment presets (e.g., Palace, Phone Call, Large Hall) optimized for low-latency Lambda inference.
    *   **ONNX Transition**: Successfully converted **OpenVoice** models to **ONNX** for optimized serverless deployment.

---

### **Previous Professional Experience**

### **RADSONE** | *Senior Research Engineer* | *Jun 2015 – Sep 2016*
*   **Ripplebuds Project**: Analyzed the "occlusion effect" in-ear microphones and developed a restoration system using a Neural Network-trained multi-band equalizer.
*   **airDAC Project**: Designed high-end Wi-Fi/USB DAC and headphone amplifier circuits; exhibited at the 2016 Munich High-end Show with critical acclaim.

### **EXTEGER** | **Co-founder** / *Senior Research Engineer* | *May 2014 – May 2015*
*   **Fabless Semiconductor Startup**: Co-founded a startup specializing in ASIC design for Class D amplifier PWM modulators; successfully supplied chips to **Samsung** and **LG**.
*   **Algorithm Design**: Developed a click-free PWM switching frequency shift algorithm and an envelope-based PVDD control system, achieving 40% efficiency improvement.

### **PULSUS** | *Research Engineer* | *Mar 2010 – Apr 2014*
*   **ASIC Front-end Design (PS8645)**: Developed an integrated one-chip solution (USB/PWM/Class-D) adopted by **SONY** for iPhone docking speakers.
*   **Digital Audio Engine**: Engineered a high-performance PWM engine using MATLAB simulations, improving THD by 20dB and achieving SNR > 115dB via digital PLL and noise-shaping.
*   **AATP Platform**: Developed a real-time audio algorithm verification tool (C++/Qt) as a Winamp plugin for rapid DSP prototyping.

### **LG Telecom** | *Assistant Research Engineer* | *Feb 2007 – Aug 2008*
*   Optimized EVDO rev.A wireless network coverage and throughput.

---

## Key Achievements

*   **CTO Leadership**: Scaled Atlas Labs to a multi-national AI leader, serving as CTO and Board Director for the US parent company.
*   **Open Source Impact**: Co-developed the [Zeroth Project](https://github.com/goodatlas/zeroth), establishing the official Kaldi Korean recipe used globally in ASR research.
*   **Global R&D Leadership**: Pioneered Few-shot In-Context Learning for low-resource languages, achieving breakthrough performance for global non-profit language support.
*   **Architectural Innovation**: Successfully integrated LLM-based multi-agent systems with deep-level VoIP infrastructure for autonomous telephony.

---

## Education

*   **Seoul National University**: Master of Science in Electrical and Computer Engineering (Feb 2007)
*   **Seoul National University**: Bachelor of Science in Electrical and Computer Engineering (Feb 2005)

---

## Certifications & Others

*   **Certifications**: Deep Learning (Google/Udacity), Neural Networks (Coursera/Hinton), Machine Learning (Coursera/Ng).
*   **Publications**: "Post-processing with Neural Network for Music Signal coded by Speech Codec" (2007).
*   **Languages**: Korean (Native), English (Proficient).

<!--stackedit_data:
eyJoaXN0b3J5IjpbMTEwMTczNTI0M119
-->