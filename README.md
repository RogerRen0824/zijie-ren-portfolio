# Zijie Ren - Data Science & AI Portfolio

I am a Data Science MSc graduate with experience in machine learning, clinical time-series modelling, interpretable AI, and applied LLM/RAG workflows.

This portfolio summarises selected projects across machine learning, healthcare analytics, NLP/LLMs, and data visualisation.

## Featured Projects

### 1. Clinical Gait Data Pipeline

A Python package for processing clinical gait and joint movement data, focused on ETL, walking-zone segmentation, and interpretable biomechanical feature engineering.

**Key highlights:**
- Built a modular Python data pipeline for clinical gait and joint movement data
- Implemented patient-level and joint-level data loading, cleaning, and filtering
- Filtered joint movement records by patient IDs to support downstream analysis
- Segmented walking speed signals into walking zones
- Computed zone-level gait features including speed, cadence, stride length, and range of motion
- Designed the package to keep data processing and machine learning modelling separate for cleaner experimentation

**Tech stack:** Python, pandas, NumPy, clinical gait analysis, time-series processing, feature engineering, package structure

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
