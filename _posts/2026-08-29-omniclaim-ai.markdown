---
layout: default
modal-id: 7
date: 2026-08-29
img: omniclaim.png
alt: OmniClaim-AI projekt logó
project-date: 2026
client: AWS Hackathon (Agents for Humans)
category: AI & Multi-Agent Rendszerek / Cloud
github_url: https://github.com/barnabas47/OmniClaim-AI
description: |
  [OmniClaim-AI](https://github.com/barnabas47/OmniClaim-AI) egy autonóm légiutas-jogi védő és időjárási kifogás-cáfoló multi-ágens AI platform, amely az **AWS Agents for Humans Hackathon** keretében készült **Strands Agents SDK** és **AWS Bedrock AgentCore** technológiákkal.

  **Főbb funkciók:**
  - **Multimodális Vision OCR Dokumentum-feldolgozás**: Beszállókártyák, repülőjegyek és étkezési/hotelek nyugták automata elemzése képről/PDF-ből.
  - **Légitársasági Időjárási Kifogások Cáfolata**: Hivatalos repülőtéri METAR meteorológiai és párhuzamos járatindulási adatok valós idejű lekérdezése a téves "vis maior" légitársasági elutasítások megdöntésére.
  - **Ortodróma (Great-Circle) Távolságszámítás**: Geodéziai repülési távolságok és pontos törvényes kártérítési összegek (€250 / €400 / €600 EU261/UK261/US DOT szabályzatok szerint) és egyéb költségek automata kiszámítása.
  - **Előre Kitöltött Igénybejelentő Csomagok**: Lufthansa, Ryanair, WizzAir és egyéb légitársasági nyomtatványok és hivatalos jogi felszólító levelek automata generálása.
  - **1-Kattintásos Human-in-the-Loop (HITL) Jóváhagyás**: Letisztult döntési kártyák a légiutasok számára 1-kattintásos benyújtáshoz.
  - **Native Android Mobilalkalmazás**: 100% natív Java Android app és Fast-API backend integráció.

  **Technológiák:**
  - AI & Multi-Agent: Strands Agents SDK (`strands-agents`), AWS Bedrock AgentCore (Claude 3.7 Sonnet / Nova)
  - Backend: Python (FastAPI), Vision OCR, METAR weather parser, Great-Circle math
  - Frontend & Mobile: React (Vite, TypeScript, Tailwind CSS), Natív Android (Java)

  **Futtatás:**
  - Lépj be a projekt mappájába, majd indítsd el a 1-click indítót: `START_OMNICLAIM.bat` (böngésző: `http://localhost:3000`)
---
