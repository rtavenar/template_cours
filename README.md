# Fiches de TD avec compilation `pandoc` automatique

Ce dépôt est un _template_ de dépôt permettant :
* d'écrire des fiches de TD en Markdown
* de les compiler avec `pandoc` vers HTML et PDF (via une GitHub Action)
* de les publier via la branche `gh-pages` (**TODO: documenter la manip à faire**)

## Fonctionnement

Les énoncés au format Markdown doivent être placés dans le répertoire `src/` et leur extension doit être `.md`.
Leur structure doit être du type :

```md
---
title : "Titre ici"
subtitle: "Sous-titre ici si nécessaire"
language: fr
author: "Nom de l'auteur ici"
rights: "Creative Commons CC BY-NC-SA (par exemple)"
---

Début de l'énoncé ici...
```
