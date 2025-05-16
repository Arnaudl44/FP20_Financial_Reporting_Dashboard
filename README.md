# FP20 Analytics Challenge 26 – Financial Reporting Dashboard

## 📄 Contexte du projet

Ce projet a été réalisé dans le cadre du **FP20 Analytics Challenge 26** organisé en partenariat avec **ZoomCharts**. L’objectif était de concevoir un tableau de bord de reporting financier pour une entreprise SaaS fictive, en s’appuyant sur des données de dépenses, de budget et de revenus.

---

## 🧩 Objectifs & Questions Clés

- Quand l'entreprise est-elle devenue rentable ?
- Quelles sont les lignes budgétaires les plus sur- ou sous-exécutées ?
- Quels fournisseurs ou clients dominent les flux financiers ?
- Quels postes expliquent les écarts budgétaires ?

---

## 🛠️ Étapes de réalisation

### 1. **Préparation des données (Power Query)**
- Filtrage et nettoyage des transactions & budgets.
- Normalisation des formats et suppression des doublons.

### 2. **Modélisation**
- Création d’un modèle en étoile autour de deux tables de faits : `Fact_Transactions` et `Fact_Budget`.
- Hiérarchies temporelles (`Année` > `Mois`).
- Relations entre comptes, fournisseurs, clients et services.

### 3. **Mesures DAX**
- Création de groupes de mesures dynamiques pour faciliter l'analyse.
- Calculs de variation temporelle (`YoY`, `YTD`, etc.), écarts vs. budget, KPIs consolidés.

### 4. **Visualisation (Power BI avec ZoomCharts)**
- Construction d’un rapport en 3 pages :
  - **Executive Summary** : KPIs, tendance mensuelle, structure des revenus/dépenses.
  - **Detailed Budget Analysis** : analyse détaillée par ligne comptable.
  - **Top Contributors** : top fournisseurs et clients, analyse de performance.

- Fonctions avancées :
  - **Signets** : pour basculer entre vues "Revenue" et "Expense".
  - **Tooltips personnalisés**.
  - **Navigation latérale** avec surbrillance.
  - Icônes SVG & branding personnalisé (NUMERIKON).

---

## 📊 Insights Clés

- 🔹 Le **résultat net** devient **positif pour la première fois en 2024**, atteignant **+300K €**.
- 🔹 Les **revenus réels dépassent le budget de 380K €**, tirés par des revenus récurrents (>82 %).
- 🔹 Les **dépenses de personnel** (notamment **payroll** et **health insurance**) ont **plus que doublé** depuis 2022.
- 🔹 Le compte **SaaS COGS** reste en dépassement constant depuis mi-2022.
- 🔹 Les postes **Advertising & Marketing** et **Professional Fees** sont **largement sous-utilisés**, améliorant le résultat.
- 🔹 Les clients **Various SMB** et **GlobalTech** affichent la meilleure **croissance YoY**.

---

## 🌐 Lien vers le rapport interactif (Web)

🔗 [Voir le rapport Power BI en ligne](https://tinyurl.com/fp20-financial-report)

---

## 🧾 Fichiers inclus

- `FP20_Financial_Reporting_Challenge_ArnaudLeMerrer.pbix`
- `FP20_Financial_Reporting_Challenge_ArnaudLeMerrer.pdf`
- `README.md`

---

## 🧰 Outils utilisés

- [Power BI](https://powerbi.microsoft.com/)
- Power Query / DAX

---

## 🙌 Remerciements

Merci à **@Federico Pastor**, **@ZoomCharts** et la communauté **FP20 Analytics** pour cette opportunité d'apprentissage et de mise en pratique.

---

## 📌 Auteur

**Arnaud Le Merrer**  
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Arnaud%20Le%20Merrer-blue?logo=linkedin)](https://www.linkedin.com/in/arnaud-le-merrer-66a401102/)  
[![GitHub](https://img.shields.io/badge/GitHub-Arnauldl44-black?logo=github)](https://github.com/Arnauldl44)
