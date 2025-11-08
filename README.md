# Tableau_de_ventes_CRM
# 🧮 Tableau de bord des ventes CRM – Maven Analytics (Google Sheets)

## 📘 Contexte du projet
Ce projet est inspiré d’un **exercice Maven Analytics** portant sur la création d’un **tableau de bord interactif** pour le suivi des ventes.  
L’entreprise fictive **Maven Tech** vend du matériel informatique à des grandes entreprises et vient de commencer à utiliser un **nouveau système CRM**.  
L’objectif était d’offrir aux managers une **vision claire et dynamique** des performances commerciales trimestrielles.

---

## 🎯 Objectifs du projet
- Analyser les performances trimestrielles des équipes de vente  
- Identifier les **top performers** et les commerciaux en difficulté  
- Suivre le **taux de conversion** (opportunités gagnées vs perdues)  
- Visualiser les **ventes et revenus** par agent, manager et bureau régional  
- Comparer les résultats entre trimestres  

---

## 🧰 Données utilisées
Deux fichiers de données CSV ont été utilisés :  

- `sales_pipeline.csv` → opportunités commerciales (client, produit, statut, date, montant, etc.)  
- `sales_teams.csv` → structure des équipes (agent, manager, bureau régional)  

Les données ont été **fusionnées** et **nettoyées** dans Google Sheets avant analyse.

---

## ⚙️ Étapes réalisées

### 1️⃣ Préparation et nettoyage des données
- Importation des deux jeux de données dans Google Sheets  
- Vérification des valeurs manquantes et des formats de date  
- Fusion des données via `XLOOKUP` pour ajouter le manager et le bureau régional  
- Création de colonnes dérivées (trimestre, statut simplifié, montant total)

### 2️⃣ Analyse exploratoire
- Utilisation des **Tableaux Croisés Dynamiques (TCD)** pour :
  - Calculer les opportunités gagnées par trimestre  
  - Comparer le taux de conversion (gagné vs perdu)  
  - Classer les commerciaux selon leurs performances  

### 3️⃣ Visualisation et tableau de bord
- **Carte KPI** : comparaison du dernier trimestre (2017-Q4) avec le précédent (2017-Q3)  
- **Graphique circulaire** : répartition des opportunités gagnées et perdues  
- **Barres verticales** : opportunités et chiffre d’affaires par commercial  
- **Segments de filtre** : manager et bureau régional  
- Mise en forme claire et lisible du **dashboard final**

---

## 📈 Résultats
- Suivi visuel des performances trimestrielles des équipes  
- Identification des commerciaux les plus performants  
- Suivi du chiffre d’affaires et du taux de réussite global  
- Outil de reporting clair et accessible pour les managers  

---

## 🧩 Outils et compétences mobilisées
- **Google Sheets** (TCD, formules, graphiques dynamiques)  
- **Data Cleaning & Transformation**  
- **KPI Design** et **Data Visualization**  
- **Analytical Storytelling**

---

## 💡 Ce que j’ai appris
- Structurer un tableau de bord clair à partir de données brutes  
- Appliquer les bonnes pratiques de visualisation dans Google Sheets  
- Communiquer efficacement les résultats à des décideurs non techniques  

---

## 🖼️ Aperçu du dashboard
<img width="916" height="328" alt="image" src="https://github.com/user-attachments/assets/78af0ddc-dcbb-4c4b-b433-5edb80b99ba6" />
  

---

## 🧑‍💻 Auteur
**Almamy Camara**  
Data Analyst & Backend Developer  
📍 Sénégal / Gambie  
📧 almamync@gmail.com  
🔗 [Ton profil LinkedIn](https://www.linkedin.com/in/almamycamara)

---

## 🏷️ Mots-clés
`Data Analysis` `Google Sheets` `Business Intelligence` `Maven Analytics` `CRM Dashboard` `Data Visualization`



