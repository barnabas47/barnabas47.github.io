---
layout: default
modal-id: 8
date: 2026-08-29
img: safecode.png
alt: SafeCode-AI project logo
project-date: 2026
client: Nebius x NVIDIA Global AI Hackathon
category: AI & Agentic Security / Cloud Infrastructure
github_url: https://github.com/barnabas47/SafeCode-AI
description: |
  [SafeCode-AI](https://github.com/barnabas47/SafeCode-AI) is a sandboxed code vulnerability refactoring & AI security platform built for the **Nebius x NVIDIA Global AI Hackathon** leveraging **Nebius Token Factory**, **NVIDIA Nemotron 3 Ultra/Nano**, and **NVIDIA OpenShell** kernel-level sandbox governance.

  **Main features:**
  - **Multi-Model Routing Architecture**:
    - *NVIDIA Nemotron 3 Ultra*: Deep code security analysis, complex vulnerability reasoning, and automated patch refactoring.
    - *NVIDIA Nemotron 3 Nano*: High-speed, cost-efficient metadata extraction and pre-filtering.
  - **Nebius Token Factory & Serverless Endpoints**: High-throughput serving of open-weight NVIDIA Nemotron models via OpenAI-compatible endpoints.
  - **NVIDIA OpenShell Sandbox Governance**: Kernel-level isolation and L7 proxy policies preventing unauthorized egress, securing credentials, and enforcing safe execution.
  - **Asynchronous Background Worker Queue**: Nebius Serverless Jobs for processing high-volume batch code auditing jobs.
  - **Interactive REST API & Swagger UI**: Standard OpenAI-compatible API interface.

  **Technologies:**
  - AI Models: NVIDIA Nemotron 3 Ultra (`nvidia/nemotron-4-340b-instruct`), Nemotron 3 Nano (`nvidia/nemotron-4-8b-instruct`)
  - Infrastructure: Nebius Token Factory, Nebius Serverless Endpoints & Jobs, NVIDIA OpenShell
  - Backend: Python 3.10+, FastAPI, Pytest test suite

  **How to run:**
  - Configure `NEBIUS_API_KEY` in `.env` and start the server: `python app.py` (Swagger UI: `http://localhost:8000/docs`)
---
