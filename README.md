# Enterprise Financial Intelligence Assistant
An AI-powered application designed for FinVista Capital to enable natural language interaction with enterprise documents using RAG[cite: 1].

## Table of Contents
1. [Project Overview](#project-overview)
2. [Architecture](#architecture)
3. [Setup & Installation](#setup-and-installation)
4. [Deployment (Kubernetes)](#deployment)
5. [CI/CD Pipeline](#cicd-pipeline)

## Project Overview
This project aims to reduce manual document search efforts by at least 70% by automating the ingestion, indexing, and retrieval of financial reports[cite: 1].

## Architecture
The system follows a modular design[cite: 1]:
* **Ingestion**: PDF parsing and text preprocessing[cite: 1].
* **Retrieval**: Semantic search via ChromaDB[cite: 1].
* **Generation**: Context-aware responses using Gemini LLM[cite: 1].

## Setup & Installation
1. Clone the repository.
2. Install dependencies: `pip install -r requirements.txt`.
3. Set your `GOOGLE_API_KEY` environment variable.
4. Run the application: `streamlit run app.py`.

## Deployment
Instructions for deploying the containerized application to an EKS cluster[cite: 1].

## CI/CD Pipeline
Overview of the automated workflow that triggers builds and deployments on code commits[cite: 1].
