---
title: "Tilt Breaker — Jeu d'arcade interactif basé sur le gyroscope (2025)"
date: 2025-10-01
draft: false
description: "Jeu d'arcade mobile qui revisite Breakout avec un contrôle au gyroscope et une boucle de jeu temps réel."
summary: "Android • Gyroscope • Arcade • Temps réel • Jeu"
tags: ["Android", "Kotlin", "Game", "Sensors", "Realtime", "Jetpack Compose"]
authors: ["Brechbühler Julien", "Guillaume Alexandre", "Schmied Joey"]
---

<div style="max-width: 400px; margin: auto;">
  <video controls playsinline preload="metadata" style="width:100%; border-radius:12px;">
    <source src="demo.webm" type="video/webm">
    <source src="demo.mp4" type="video/mp4">
    Votre navigateur ne supporte pas la lecture vidéo.
  </video>
</div>

Tilt Breaker revisite le principe de Breakout avec un contrôle au gyroscope et un moteur de jeu temps réel sur mobile.

Le projet cherche à remplacer les contrôles tactiles classiques par une interaction plus immersive, capable d'exploiter l'inclinaison du téléphone pour renforcer la sensation de jeu.

## Ce que l'application apporte

- Un contrôle de la raquette via le gyroscope
- Un moteur de collision en temps réel
- Un système de score et de vies
- Une difficulté progressive
- Une expérience arcade pensée pour le mobile

## Défi technique principal

Le défi central a été de synchroniser capteurs, physique, collisions et rendu graphique dans une boucle de jeu fluide. Le projet met en valeur la capacité à gérer du temps réel sur mobile sans sacrifier la jouabilité.

## Encadrant

- Rizzotti Aïcha (Professeure)
- Guyaz Loïc (Assistant)
