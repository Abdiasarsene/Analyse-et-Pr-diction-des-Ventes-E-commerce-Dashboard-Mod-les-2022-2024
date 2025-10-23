# Analyse et Prédiction des Ventes E-commerce 2022–2024

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=power-bi&logoColor=black)

"*L’entreprise voulait comprendre ses ventes. J’ai plongé dans deux ans d’historique, construit une prévision sur 12 mois, et livré un tableau de bord Power BI pour décider avec clarté. Tout est ici.*"

---

## 🎯 Objectifs

- Analyser les ventes passées selon plusieurs dimensions : produit, saison, région, météo, événements.
- Identifier les pics de ventes liés aux promotions et jours fériés.
- Développer des modèles de prédiction (ARIMA, Random Forest) pour anticiper les ventes sur 12 mois.
- Proposer des recommandations opérationnelles pour maximiser les performances commerciales.

---

## 📊 Résultats clés

### Chiffre d’affaires global
- **29 780 383 €** sur deux ans

### Top produits
| Produit                  | Chiffre d'affaires (€) |
|--------------------------|------------------------|
| Tablettes                | 5 990 420              |
| Ordinateurs              | 5 988 505              |
| Accessoires              | 5 972 010              |
| Smartphones              | 5 965 615              |
| Écouteurs                | 5 864 285              |

### Saisonnalité
- **Hiver** : meilleure saison (7 549 530 €)
- **Décembre** : mois le plus performant (2 631 440 €)
- **Février** : mois le plus faible (2 196 570 €)

### Régions
- **Ouest** : région la plus performante (7 640 005 €)
- **Est** : région à cibler (7 314 135 €)

### Météo
- **Ensoleillé** : meilleure performance (7 603 740 €)
- **Pluvieux** : impact négatif (7 249 945 €)

---

## 🔮 Modélisation prédictive

### ARIMA
- Modèle utilisé : ARIMA(p=2, d=1, q=2)
- Résultat : légère instabilité, pas de tendance forte

### Random Forest
- Résultat d'entraînement : **R² = 1.00**, **RMSE = 0.00**
- Problème : **surapprentissage**, prédictions constantes

---

## 🔃 Visualisation Power BI

[POwer BI Viz Ecomm](./statics/ecom_bi.png)

## 🧠 Recommandations stratégiques

1. **Renforcer les promotions en hiver et en décembre**
2. **Cibler la région Est avec des campagnes locales**
3. **Mettre en avant les produits populaires (ex. : tablettes)**
4. **Adapter les offres aux conditions météo défavorables**
5. **Diversifier le portefeuille produits**
6. **Synchroniser promotions et jours fériés**
7. **Améliorer la flexibilité des modèles de prévision**

---

## 🛠️ Contenu du dépôt

- `data/` : données de ventes nettoyées
- `notebooks/` : analyses exploratoires et modélisation ARIMA & Random Forest
- `dashboard/` : tableau de bord Power BI
- `models/` : scripts de prédiction
- `docs/` : rapport d’analyse et synthèse stratégique
