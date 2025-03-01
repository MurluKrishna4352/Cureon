# 🏥 Cureon - AI-Powered Clinical Documentation & Diagnosis Assistant

![Cureon](https://user-images.githubusercontent.com/00000000/000000000-cureon-banner.png)

## 🚀 Introduction
**Cureon** is an AI-powered system designed to automate clinical documentation and assist in disease diagnosis using **Speech-to-Text, Named Entity Recognition (NER), and Predictive Analytics**.

Physicians often spend a **significant** amount of time on manual documentation, leading to **burnout** and **inefficiencies**. Cureon streamlines this process by **transcribing doctor-patient conversations in real-time**, extracting relevant medical entities, and predicting potential diseases from clinical notes.

## 🎯 Features
### ✅ **Automated Speech-to-Text**
- Uses **Whisper AI** for high-accuracy speech recognition.
- Supports **multi-speaker diarization** to distinguish between doctors, nurses, and patients.
- Handles **various accents and background noise** for real-world scenarios.

### ✅ **Named Entity Recognition (NER)**
- Identifies critical **medical entities** such as:
  - **Diseases** 🦠
  - **Medications** 💊
  - **Symptoms** 🤒
- Leverages **pre-trained NER models** from Hugging Face.
- Implements a **rule-based fallback** to ensure clinical terms are accurately extracted.

### ✅ **AI-Powered Disease Prediction**
- Utilizes **BioClinicalBERT**, a fine-tuned transformer model for medical text analysis.
- Analyzes **structured** and **unstructured** patient data.
- Predicts potential diseases based on **clinical notes & symptoms**.

### ✅ **Seamless EHR Integration**
- Supports **FHIR-compliant** databases.
- Secure **PostgreSQL** backend for storing medical records.
- REST API built with **FastAPI** for easy integration with hospital systems.

## 🏗️ Tech Stack
| Component               | Technology Used |
|-------------------------|----------------|
| **Speech Recognition**  | Whisper AI, DeepSpeech |
| **Natural Language Processing (NLP)** | BioBERT, MedPaLM 2, Llama 3 (fine-tuned) |
| **Voice Assistant** | FastAPI + WebRTC |
| **Machine Learning for Predictions** | TensorFlow, PyTorch |
| **Database & EHR Integration** | PostgreSQL (FHIR-compliant) |
| **Frontend** | React.js + TailwindCSS |


