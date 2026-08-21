---
layout: default
modal-id: 5
date: 2026-08-21
img: 2d_platformer.png
alt: 2D Platformer (ORIGAMI VOID) projekt logó
project-date: 2026
client: Személyes projekt
category: Játékfejlesztés / HTML5 Canvas & Web Audio API
github_url: https://github.com/barnabas47/2d_platformer
description: |
  [ORIGAMI VOID — Speedrun Edition](https://github.com/barnabas47/2d_platformer) egy tiszta HTML5 Canvas és Web Audio API alapokon nyugvó, 2D-s dimenzió-hajtogató speedrun puzzle-platformer játék. A projekt élőben is kipróbálható a [https://barnabas47.github.io/2d_platformer/](https://barnabas47.github.io/2d_platformer/) címen.

  **Főbb funkciók:**
  - **Dimenzió-hajtogatás és Relatív Gravitáció**: Manipulálható térbeli gravitációs vektorok — a játékos fel tud tapadni a 90°-os függőleges falakra és a plafonra is. A relatív irányítás dinamikusan alkalmazkodik a felülethez.
  - **Eredményes Speedrun Motor (`00:00.000`)**: Milliszekundumos pontosságú stopperóra a Personal Best (egyéni rekord) idők elmentésével `localStorage`-ba.
  - **3 Másodperces Morzsolódó Platformok**: Időzített sárga platformok, amelyek az érintés után 3 másodperccel feloldódnak, parázs részecske effektekkel és felső haladási sávval.
  - **360°-os Forgó Lézerakadályok**: 2D térben lassankán körbeforgó piros lézersugarak elkerülése.
  - **Dinamikus Lézerárnyék-blokkolás**: A szilárd pálya platformok és a spawner által idézett Fold Platformok dinamikusan blokkolják a lézereket, védett árnyékzónát hozva létre alatta.
  - **Szintetizált Web Audio Hangeffektek**: Beépített Web Audio API hangszintetizátor interaktív hangerőszabályzóval mind a Főmenüben, mind a HUD fejlécben.
  - **100% Fullscreen Viewport Skálázás**: Zökkenőmentes reszponzív illeszkedés bármely böngésző ablakméretéhez (`100vw` × `100vh`) elcsúszásmentes `tabular-nums` számlálókkal.

  **Technológiák:**
  - Renderelés: HTML5 Canvas 2D Kontextus (egyedi mozgalomnyomok és részecske effektek)
  - Logika: Vanilla JavaScript ES6+ (könyvtárak és keretrendszerek nélkül)
  - Hangképzés: Web Audio API (procedurális hangszintézis)
  - Styling: CSS3 Neofuturistic Cyberpunk téma, glassmorphism UI overlay

  **Futtatás:**
  - Nyisd meg az `index.html` fájlt közvetlenül bármelyik modern böngészőben, vagy látogass el a [https://barnabas47.github.io/2d_platformer/](https://barnabas47.github.io/2d_platformer/) demó oldalra!
---
