---
layout: default
modal-id: 8
date: 2026-08-29
img: safecode.png
alt: SafeCode-AI projekt logó
project-date: 2026
client: Nebius x NVIDIA Global AI Hackathon
category: AI & Agentic Security / Cloud Infrastructure
github_url: https://github.com/barnabas47/SafeCode-AI
description: |
  [SafeCode-AI](https://github.com/barnabas47/SafeCode-AI) egy elszigetelt (sandboxed) kód sérülékenység-javító és biztonsági ágens platform, amely a **Nebius x NVIDIA Global AI Hackathon** nyertes architektúrájára épül **Nebius Token Factory**, **NVIDIA Nemotron 3 Ultra/Nano** és **NVIDIA OpenShell** L7 proxy elszigeteléssel.

  **Főbb funkciók:**
  - **Többmodell-útválasztó (Multi-Model Routing)**:
    - *NVIDIA Nemotron 3 Ultra*: Mély kód-biztonsági elemzés, összetett sérülékenységi minták feltárása és refaktorálás.
    - *NVIDIA Nemotron 3 Nano*: Villámgyors, költséghatékony metaadat-kinyerés és előszűrés.
  - **Nebius Token Factory & Serverless Endpoints**: Skálázható, nyílt súlyú NVIDIA Nemotron modellek alacsony válaszidővel és magas átvitellel.
  - **NVIDIA OpenShell Homokozó (Sandbox)**: Rendszermag szintű elszigetelés és L7 proxy házirend-kezelés az illetéktelen adatátvitel megelőzésére és a biztonságos eszközfuttatásra.
  - **Aszinkron Background Worker Queue**: Nebius Serverless Jobs nagy volumenű kötegelt kódvizsgálatokhoz.
  - **Interaktív REST API & Swagger UI**: Szabványos OpenAI-kompatibilis API interfész.

  **Technológiák:**
  - AI Modellek: NVIDIA Nemotron 3 Ultra (`nvidia/nemotron-4-340b-instruct`), Nemotron 3 Nano (`nvidia/nemotron-4-8b-instruct`)
  - Infrastruktúra: Nebius Token Factory, Nebius Serverless Endpoints & Jobs, NVIDIA OpenShell
  - Backend: Python 3.10+, FastAPI, Pytest test suite

  **Futtatás:**
  - Állítsd be a `.env` fájlban a `NEBIUS_API_KEY`-t, majd indítsd el az szervert: `python app.py` (Swagger felület: `http://localhost:8000/docs`)
---
