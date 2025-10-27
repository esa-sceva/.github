# ESA-SCEVA

**SatCom Expert Virtual Assistant (SCEVA)**  
An open science initiative by the European Space Agency’s ARTES programme, developed by **Pi School** in collaboration with **RINA** and **i2CAT**.

SCEVA is part of the **SatcomLLM** project (“Assessment of Open-Source Large Language Models within the SatCom Sector”), which aims to advance the use of Large Language Models (LLMs) for satellite communications.

---

## 🌍 Overview

SCEVA is a specialised Large Language Model system for **satellite communications (SatCom)**.  
It supports engineers, mission planners, and operators through natural language interaction, providing expert-level assistance in areas such as:

- Link budget analysis  
- System design and simulation  
- Constellation management and mission planning  
- Cybersecurity and anomaly detection  
- Regulatory compliance and documentation summarisation  

The project combines **scientific data curation, model training, benchmarking, and deployment** to create open, reusable AI tools for the European SatCom community.

---

## 🧠 Model Development

Two models are being fine-tuned using domain-specific data:

| Model | Description |
|--------|-------------|
| **esa-sceva/satcom-chat-8b** | Compact SatCom-specialised model for inference and experimentation |
| **esa-sceva/satcom-chat-70b** | High-capacity model optimised for accuracy, reasoning, and domain coverage |

Training is carried out on EuroHPC and cloud GPU environments using **Lit-GPT (Lightning AI)**, combining continued pretraining and instruction fine-tuning (IFT).  
The models are being optimised for factual accuracy, reasoning depth, and integration with a **Retrieval-Augmented Generation (RAG)** pipeline.

---

## 📚 Datasets

All datasets are curated and structured for reproducible research and fine-tuning.

| Dataset | Description |
|----------|-------------|
| **esa-sceva/satcom-qa** | Expert question–answer pairs on SatCom workflows |
| **esa-sceva/satcom-mcqa** | Multiple-choice questions for evaluation and benchmarking |
| **esa-sceva/satcom-synth-qa** | Synthetic QA dataset generated using SCEVA’s agentic data pipeline |
| **esa-sceva/satcom-synth-qa-cot** | Chain-of-thought reasoning dataset for improved interpretability |

Datasets include contributions from open-access technical sources, ESA documentation, and curated domain corpora compliant with EU and ESA data guidelines.

---

## 🧩 Architecture

SCEVA integrates:

- **LLM Core:** Fine-tuned LLaMA-based models (8B and 70B)  
- **RAG System:** Hybrid document retrieval with vector databases for source-grounded answers  
- **Agentic Layer:** Task automation and tool-calling via LangGraph  
- **Web Interface:** Internal demo interface and API for expert users  

---

## 🔓 Open Science Commitment

All released models, datasets, and tools are open access and follow **ESA and EU open science guidelines**.  
The goal is to enable **European technological sovereignty** in AI for SatCom and to foster a shared ecosystem for applied space AI research.

---

## 🛰️ Contact
**Contributors:**  
Pi School · RINA Consulting · European Space Agency (ARTES Programme)

