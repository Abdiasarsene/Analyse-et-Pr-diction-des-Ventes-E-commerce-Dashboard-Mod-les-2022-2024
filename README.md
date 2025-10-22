# Analyse et Prédiction des Ventes E-commerce — Dashboard & Modèles 2022–2024

Ce dépôt regroupe l’ensemble du travail réalisé dans le cadre d’une mission d’analyse et de prédiction des ventes pour une entreprise du secteur e-commerce. Il couvre l’analyse des ventes passées (janvier 2022 à janvier 2024), la modélisation prédictive sur 12 mois, et la livraison d’un tableau de bord interactif Power BI pour la prise de décision.

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

---

## 📣 Contact
