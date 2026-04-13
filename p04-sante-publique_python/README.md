# P04 — Étude de Santé Publique avec Python · FAO

> Formation Data Analyst OpenClassrooms · Bloc RNCP BC02 — Identifier, collecter & analyser

---

## Contexte métier

Analyse des données alimentaires mondiales de la FAO pour comprendre la sous-nutrition à l'échelle mondiale, identifier les pays les plus vulnérables et mettre en évidence les zones géographiques prioritaires.

---

## Réalisations clés

- Chargement et nettoyage de fichiers CSV multi-sources (population + sous-nutrition)
- Gestion des cas particuliers (`<0.1`) et conversion des valeurs numériques
- Jointure des tables sur la colonne Zone pour croiser les données
- Calcul du nombre absolu de personnes sous-nutrition par pays
- Calcul de la proportion (%) par rapport à la population
- Filtrage des pays < 1 million habitants pour éviter les biais statistiques
- Classement des 10 pays les plus touchés
- **Visualisation cartographique** avec GeoPandas

---

## Résultats clés

- Haïti, Corée du Nord, Madagascar, Tchad, Libéria parmi les plus touchés
- Mise en évidence des zones de vulnérabilité alimentaire mondiale

---

## Stack technique

`Python` · `Pandas` · `GeoPandas` · `Matplotlib` · `Seaborn` · `NumPy` · `Jupyter`

---

## Analyse réflexive

Ce projet m'a permis d'utiliser GeoPandas pour la première fois — une passerelle naturelle entre ma formation géomaticienne et l'analyse data. Croiser des données de population avec des données de nutrition pour produire une carte de vulnérabilité mondiale, c'est exactement le type d'analyse à impact que je cherche à faire : des données au service de décisions concrètes.

---

## Soft skills mobilisés

`Rigueur` · `Sens de l'impact` · `Cartographie` · `Analyse statistique`

---

*Kouamé Ghyslain KANGA · Data Analyst · Projet 13 OpenClassrooms · Avril 2026*