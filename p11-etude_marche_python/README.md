# P11 — Étude de Marché avec Python · La Poule qui Chante

> Formation Data Analyst OpenClassrooms · Bloc RNCP BC05 — Statistiques & Machine Learning

---

## Contexte métier

La Poule qui Chante, entreprise agroalimentaire française, souhaite s'internationaliser. L'objectif est d'identifier les pays les plus attractifs pour l'exportation de volaille grâce à une analyse multidimensionnelle de données mondiales.

---

## Réalisations clés

- **7 sources de données** fusionnées (FAO, Banque Mondiale WGI, QoG)
- **96 pays** analysés · année de référence 2021 · 0 valeur manquante après harmonisation
- **Cadre d'analyse PESTEL** appliqué (Politique, Économique, Social, Légal)
- **ACP (Analyse en Composantes Principales)** : 8 variables → 3 axes · 89.2% de variance expliquée
  - PC1 (47.2%) : axe Développement
  - PC2 (23.3%) : axe Importations
- **Clustering** : CAH (méthode Ward) + K-means → k=4 retenu · 4 profils de marchés types
- **Score d'attractivité composite** : PIB 30% + Volaille 30% + Importations 20% + autres critères

---

## Top 5 pays recommandés

| Rang | Pays | Score |
|------|------|-------|
| 1 | Ireland | 0.586 |
| 2 | Luxembourg | 0.564 |
| 3 | Qatar | 0.549 |
| 4 | Israel | 0.533 |
| 5 | United States | 0.530 |

---

## Stack technique

`Python` · `Pandas` · `Scikit-learn` · `Scipy` · `Matplotlib` · `Seaborn` · `ACP` · `CAH` · `K-means`

---

## Livrables

- Notebook 1 — Préparation des données
- Notebook 2 — Analyse et clustering
- Slides de présentation (15 slides)

---

## Analyse réflexive

L'ACP est un outil puissant mais qui demande une vraie rigueur d'interprétation — les axes ne parlent pas d'eux-mêmes, il faut les lire dans le contexte métier. Sur ce projet, j'ai appris à combiner des méthodes statistiques (CAH pour explorer, K-means pour confirmer) plutôt que d'en choisir une seule aveuglément. Le score d'attractivité composite m'a aussi appris à justifier chaque pondération — un exercice de posture consultant autant que de statistiques.

---

## Soft skills mobilisés

`Data wrangling` · `Pensée analytique` · `Storytelling` · `Rigueur méthodologique`

---

*Kouamé Ghyslain KANGA · Data Analyst · Projet 13 OpenClassrooms · Avril 2026*