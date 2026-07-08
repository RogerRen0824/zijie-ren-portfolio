# Zijie Ren - Data Science & AI Portfolio

I am a Data Science MSc graduate with experience in machine learning, clinical time-series modelling, interpretable AI, and applied LLM/RAG workflows.

This portfolio summarises selected projects across machine learning, healthcare analytics, NLP/LLMs, and data visualisation.

## Featured Projects

### 1. Clinical Gait Data Pipeline

A local-only Python package for processing sensitive clinical gait and joint movement data, developed to support privacy-preserving research workflows.

The original clinical data cannot be shared publicly due to privacy and data protection requirements. This repository is used to demonstrate the package structure, data processing logic, and feature engineering workflow while keeping all real patient data and execution outputs local.

**Key highlights:**
- Refactored local research scripts into a modular Python package for clinical gait data processing
- Designed the workflow to run entirely on local machines without uploading sensitive patient data
- Implemented patient-level and joint-level data loading, cleaning, and filtering
- Filtered joint movement records by patient IDs to support downstream research analysis
- Segmented walking speed signals into walking zones
- Computed interpretable biomechanical features including speed, cadence, stride length, and range of motion
- Separated data processing from modelling to support cleaner experimentation and reproducibility

**Tech stack:** Python, pandas, NumPy, clinical gait analysis, time-series processing, ETL, feature engineering, privacy-preserving data workflows

Repository: [Gait_Data_Pipeline](https://github.com/RogerRen0824/Gait_Data_Pipeline)
---

### 2. LLM Research Intelligence System

An end-to-end Retrieval-Augmented Generation (RAG) application for document-grounded question answering over user-provided PDF documents.

**Key highlights:**
- Built a local-first RAG pipeline for research document question answering
- Implemented PDF ingestion, text cleaning, chunking, embedding generation, and FAISS vector indexing
- Developed FastAPI endpoints for retrieval and grounded answer generation
- Integrated DeepSeek API through an OpenAI-compatible client
- Built a Streamlit frontend for interactive document Q&A
- Added source citation, retrieved evidence display, and lightweight retrieval quality metrics
- Included basic pytest coverage and environment configuration via `.env.example`

**Tech stack:** Python, FastAPI, Streamlit, PyMuPDF, Sentence Transformers, FAISS, DeepSeek API, pytest

Repository: [llm-research-intelligence-system](https://github.com/RogerRen0824/llm-research-intelligence-system)

---

### 3. Titanic Survival Prediction - Kaggle ML Pipeline

A structured machine learning pipeline for the Titanic survival prediction task.

**Key highlights:**
- Performed data cleaning, missing-value handling, and feature engineering
- Built a reusable model training and evaluation workflow
- Compared multiple classification models
- Generated Kaggle-compatible submission files

**Tech stack:** Python, pandas, NumPy, scikit-learn, machine learning classification

Repository: Coming soon

---

### 4. Data Visualisation & Stakeholder Reporting

A portfolio section focused on communicating technical results to non-technical stakeholders.

**Key highlights:**
- Created simplified visual summaries from technical modelling outputs
- Focused on clarity, interpretability, and stakeholder communication
- Applied business-facing data storytelling principles

**Tech stack:** Python visualisation, Tableau, Power BI, Excel

Repository: Coming soon

---

## Skills Demonstrated

- Machine learning model development
- Clinical and time-series data processing
- Feature engineering
- Model evaluation and validation
- Interpretable AI
- RAG and LLM workflows
- Data visualisation
- Stakeholder communication
- Python-based data science workflows

## Contact

- LinkedIn: https://www.linkedin.com/in/zijie-ren-742335363/
- Email: zijie.ren0824@outlook.com
