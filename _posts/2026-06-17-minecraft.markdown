---
layout: default
modal-id: 4
date: 2026-06-17
img: minecraft.png
alt: Minecraft projekt logó
project-date: 2026
client: Személyes projekt
category: Játékfejlesztés / C# Godot
github_url: https://github.com/barnabas47/minecraft
description: |
  [Minecraft Clone](https://github.com/barnabas47/minecraft) egy voxel-alapú 3D sandbox játék, amely teljesen az alapoktól épült Godot Engine 4 segítségével, C# (.NET 8.0) nyelven. A projekt célja a Minecraft alapvető játékmenetbeli mechanikáinak és a háttérben történő aszinkron világbetöltésének a megvalósítása.

  **Főbb funkciók:**
  - **Többszálú Világbetöltés**: A nehéz domborzat-generálás, a fák beültetése és a 3D háló (mesh) kiszámítása teljesen külön háttérszálakon (`Task.Run`) történik, így a játékos mozgása és az új chunkok betöltése teljesen akadásmentes (stabil 60 FPS).
  - **Procedurális Világ**: Simplex zajgenerátor (FastNoiseLite) alapú terep hullámzó dombokkal, és mélységfüggő ércekkel (szén, vas, arany, gyémánt).
  - **Fizikai Tárgyak (Dropped Items)**: A kibányászott blokkok 3D fizikai testként esnek le a talajra, ütköznek a szilárd blokkokkal, lebegnek, és mágnesesen a játékoshoz vonzódnak, ha közel megy hozzájuk.
  - **Részletes Inventory & Hotbar**: Működő UI a blokkok és eszközök tárolására, mozgatására, halmozására (stacking) és a hotbar slotok kiválasztására.
  - **Barkácsolás és Sütés**:
    - *Crafting Table*: Barkácsasztal recepetekkel eszközökhöz és alapanyagokhoz.
    - *Furnace (Kemence)*: Sütő felület üzemanyag-fogyasztással (szén, fa, botok), kiégetési idővel és progress barral (pl. nyers hús megsütése, kő kiégetése).
  - **Fizikai Optimalizáció**: Henger (Cylinder) alapú játékos ütközés az átlós elakadások megelőzésére és statikus anyag-gyorsítótár (Material Cache) a textúrák ismételt lemezről való betöltésének megszüntetésére.

  **Technológiák:**
  - Backend/Logic: C# (.NET 8.0), Godot API
  - Algoritmusok: FastNoiseLite
  - Grafika: Custom mesh generálás (SurfaceTool), textúra atlaszok
  - Egyéb: Többszálú zárolások (thread safety), reentráns szálkezelés

  **Futtatás:**
  - Lépj be a minecraft projekt mappájába, majd építsd újra és futtasd a Godot Editorból, vagy parancssorból: `dotnet build`
---
