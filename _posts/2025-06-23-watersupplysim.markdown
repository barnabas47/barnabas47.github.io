---
layout: default
modal-id: 3
date: 2025-06-23
img: water.png
alt: WaterSupplySimulator projekt logó
project-date: 2024
client: Személyes projekt
category: Full Stack Webfejlesztés
github_url: https://github.com/barnabas47/WaterSupplySim
description: |
  [WaterSupplySim](https://github.com/barnabas47/WaterSupplySim) egy modern, biztonságos, jól strukturált .NET 8 backendből és egy Vite + React + TypeScript frontendből álló vízellátás-szimulátor rendszer. A cél egy fejlesztőbarát, reszponzív, sötét-kékes témájú admin felület, amely REST API-n keresztül kommunikál a backenddel, JWT alapú admin jogosultsággal.

  **Fő funkciók:**
  - Backend (.NET 8, C#): REST API szenzoradatok, szivattyú vezérlés, riasztások, eseménynapló
  - JWT alapú admin bejelentkezés (**demó jelszó: SuperSecretKey12345**)
  - Repository, Service, DTO, AutoMapper minták
  - Globális exception middleware, validáció, hibakezelés
  - CORS, HTTPS fejlesztői támogatás
  - Rate limiting, API versioning
  - Swagger UI JWT támogatással
  - Frontend (Vite + React + TypeScript): sötét, kékes, reszponzív UI (modern táblázatok, kártyák, menü)
  - Szenzor adatok mindenki számára elérhető
  - Admin funkciók (szivattyú vezérlés, riasztás visszaigazolás, napló/CSV letöltés) csak bejelentkezve
  - JWT token kezelés (localStorage, axios interceptor)
  - Fejlesztői HTTPS támogatás (mkcert tanúsítvány)

  **Indítás:**
  - Backend: .NET 8 SDK telepítése szükséges, futtatás: `dotnet run` (Swagger UI: https://localhost:5001/swagger)
  - Frontend: Node.js + pnpm telepítése szükséges, tanúsítványok a frontend/ mappában (localhost.pem, localhost-key.pem), telepítés és indítás: `cd frontend`, `pnpm install`, `pnpm dev` (https://localhost:5173)
  - A fejlesztői HTTPS tanúsítványokat a frontendhez mkcert-tel kell generálni.

  **Admin jelszó (csak demó!):** SuperSecretKey12345

  **Fő könyvtárak/fájlok:**
  - Backend: Program.cs, Controllers/, Services/, DTOs/, Mapping/, Middleware/
  - Frontend: frontend/src/App.tsx, frontend/src/App.css, frontend/src/api.ts, frontend/vite.config.ts

  **Megjegyzések:**
  - Az admin funkciók (szivattyú, riasztás, napló, CSV letöltés) csak bejelentkezve használhatók.
  - A projekt fejlesztői környezetre optimalizált, modern best practice architektúrával készült.
---