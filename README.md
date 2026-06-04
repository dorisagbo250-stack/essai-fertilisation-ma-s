# essai-fertilisation-maïs
Analyse statistique d'un essai de fertilisation azotée sur maïs en blocs aléatoires complets
# 🌱 Analyse d’un essai de fertilisation azotée sur maïs

## 📌 Présentation du projet

Ce projet consiste en une **analyse statistique complète** d’un essai agronomique de fertilisation azotée sur maïs conduit en blocs aléatoires complets.

L’objectif principal est d’évaluer l’effet de six doses d’azote (0, 30, 60, 90, 120 et 150 kg N/ha) sur le rendement et d’identifier la dose optimale.

---

## 🎯 Objectifs

- Analyser l’effet des doses d’azote sur le rendement en grains
- Identifier la dose optimale de fertilisation
- Valider l’utilisation d’un modèle linéaire mixte
- Produire des visualisations claires et des recommandations agronomiques

---

## 🧪 Données

Les données utilisées dans cette analyse sont **des données simulées**, générées à des fins pédagogiques et d’apprentissage. Elles reproduisent de manière réaliste un essai de fertilisation azotée sur maïs avec 4 répétitions (blocs).

---

## 📊 Résultats principaux

- Effet hautement significatif de la dose d’azote sur le rendement
- **Dose optimale identifiée : 120 kg N/ha** (rendement moyen = **9,10 t/ha**)
- Forte augmentation du rendement jusqu’à 120 kg N/ha, suivie d’une légère diminution à 150 kg N/ha (courbe de Mitscherlich)
- Très faible variabilité inter-blocs (Variance = 0,0068)

---

## 🛠️ Outils et Technologies

- **Logiciel** : R & RStudio
- **Packages** : 
  - `tidyverse` (manipulation et visualisation)
  - `lme4` (modèles linéaires mixtes)
  - `emmeans` (comparaisons multiples)
  - `ggplot2` (graphiques)
- **Rapport** : Quarto

---

## 📁 Structure du projet

```bash
essai-fertilisation-mais/
├── README.md
├── Essai_Mais_Fertilisation.qmd
├── data/
│   └── essai_mais_fertilisation.csv
└── figures/
    └── rendement_dose_azote.png


## 👨‍🎓 Author

**AGBO K. Doris**  
Agronomy Student | Data Analysis & Biostatistics Enthusiast  

**Interests**: Sustainable Agriculture, Plant Breeding, Statistical Analysis

---

**Connect with me:**  
- [LinkedIn](https://www.linkedin.com/in/agbo-k-doris)  
- [Email](mailto:dorisagbo07@gmail.com)
