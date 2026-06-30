# 🥛 Optimisation des stocks sur produits frais
![Python](https://img.shields.io/badge/Python-3.10-blue?logo=python&logoColor=white)
![Status](https://img.shields.io/badge/Statut-En%20cours-yellow)
![Domain](https://img.shields.io/badge/Domaine-Supply%20Chain-2ea44f)
![ML](https://img.shields.io/badge/ML-Prophet%20%7C%20XGBoost-orange)

Projet d'analyse supply chain appliqué à la gestion des stocks de produits agroalimentaires à courte durée de vie (DLC).

Développé dans le cadre de la préparation d'un PFE en **Purchasing & Supply Chain Management**.

---

## 📌 Contexte

Les produits frais (yaourts, fromages frais, desserts lactés) imposent une gestion de stock à haute exigence : tout excès génère des pertes par dépassement de DLC, toute insuffisance entraîne une rupture de service.

Ce projet propose une approche **data-driven** pour arbitrer ce risque double.

## ❓ Problématique

> Comment détecter en amont les risques de sur-stock ou de rupture sur des références à DLC courte, à partir des données de vente, de stock et de production ?

## 🔍 Approche

| Étape | Description |
|-------|-------------|
| 📊EDA | Analyse exploratoire des dynamiques de stock, identification des références à risque |
| 📈Prévision | Demande à court terme (7–14 jours) par référence, via Prophet / XGBoost |
| 🚨Anomalies | Score d'alerte quotidien sur les références en pré-rupture ou en sur-stock |
| 📉Dashboard | Visualisation interactive des indicateurs clés (couverture, service, pertes DLC) |

## 🛠️ Stack technique

`Python` · `Pandas` · `NumPy` · `Prophet` · `XGBoost` · `Plotly` · `Dash`

## 📁 Structure du projet

Data/          → données de démonstration

Notebooks/     → analyse exploratoire et modélisation

Dashboard/     → application de visualisation interactive


## 🚧 Statut

Projet en cours de construction — premiers résultats disponibles prochainement.

## 👤 Auteur

**DIABY CHEICK MOCTAR**

M2 Purchasing & Supply Chain Management — ENCG Settat
