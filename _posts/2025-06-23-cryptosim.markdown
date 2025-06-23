---
layout: default
modal-id: 2
date: 2025-06-23
img: cryp.png
alt: CryptoSim projekt logó
project-date: 2024
client: Személyes projekt
category: Full Stack Webfejlesztés
github_url: https://github.com/barnabas47/CryptoSim
description: |
  [CryptoSim](https://github.com/barnabas47/CryptoSim) egy modern, full-stack kriptovaluta kereskedési szimulátor ASP.NET Core (C#) backenddel és React + TypeScript frontenddel.

  **Fő funkciók:**
  - Biztonságos jelszókezelés (SHA256)
  - Szerepkörök és jogosultságok: admin és felhasználó
  - Valósághű seed adatok: több tucat kriptovaluta, felhasználók, pénztárcák, tranzakciók
  - JWT autentikáció
  - Frontend/backend role enforcement
  - Modern, letisztult React/TS UI

  **Példa felhasználók:**
  - Admin: admin@example.com / adminpwd
  - Alice: alice@example.com / pwd1

  **Seedelt kriptók (részlet):**
  - Bitcoin (BTC), Ethereum (ETH), Cardano (ADA), Solana (SOL), Dogecoin (DOGE), ...és még ~50 további coin!

  **Technológiák:**
  - ASP.NET Core 9 (C#), Entity Framework Core (SQL Server)
  - React + TypeScript (frontend)
  - JWT Authentication

  **Indítás:**
  - Backend: `dotnet run` a CryptoSimulator mappában
  - Frontend: `npm install && npm start` a frontend mappában
  - Swagger API: https://localhost:7186/swagger/index.html
  - Frontend: http://localhost:3000

  **Leírás:**
  Ez a projekt egy oktatási célú kriptovaluta szimulátor, ahol a felhasználók valósághűen kereskedhetnek, portfóliót kezelhetnek, és kipróbálhatják a piac működését. Az adminisztrátor új coinokat adhat hozzá, de nem kereskedhet. A rendszer mindenhol figyeli a szerepköröket, a jelszavak biztonságosak, a seed adatok pedig változatosak és valósághűek.
---