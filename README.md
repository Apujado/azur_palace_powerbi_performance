# 🏨 Azur Palace | Worldwide 5-Star Hotel Performance

> **Macro-level insights into group health and guest satisfaction** — Un projet Power BI avancé de pilotage hôtelier international, développé au format PBIP (Power BI Project), structuré en architecture en étoile et audité via l'intelligence artificielle (Protocoles MCP).

---

## 📌 Vue d'ensemble

Le projet **Azur Palace** a pour objectif d'analyser la performance globale d'un groupe hôtelier 5 étoiles à l'échelle internationale. Il croise les données de satisfaction client (Guest Voice) avec les indicateurs macro-économiques et géographiques pour fournir aux décideurs une vision 360° de la santé des établissements et de la qualité de service.

---

## 🏗️ Architecture & Modélisation des Données

Le modèle sémantique repose sur une **architecture en étoile (Star Schema)** rigoureuse, optimisée pour les performances du moteur VertiPaq :

* **`FACT_Reviews`** : Table de faits centralisant les évaluations, scores de satisfaction par catégorie et retours clients.
* **`DIM_hotel`** : Référentiel des établissements (localisation, région, caractéristiques 5 étoiles).
* **`DIM_users`** : Segmentation et typologie des clients / répondants.
* **`DIM_Date`** : Calendrier complet gérant la Time Intelligence.
* **`Radar Hotels`** : Tableaux virtuels et mesures pour l'analyse multicritère (Spider/Radar Charts).

---

## 📊 Périmètre Fonctionnel & Mesures DAX

Les mesures DAX sont structurées par dossiers d'affichage (*Display Folders*) :

* **Summary & KPI Globaux** : Score médian global, nombre total d'avis, pourcentage d'hôtels au-dessus de la médiane.
* **Customer Voice (CX)** : Analyse détaillée des axes de satisfaction (*Propreté, Emplacement, Confort, Personnel, Rapport Qualité/Prix*).
* **Time Intelligence & Tendances** : Comparatifs N-1, variations trimestrielles/mensuelles et dynamiques d'évolution.

---

## 🤖 Gouvernance & Workflow Modern Data (PBIP & AI Audit)

Ce projet adopte les meilleures pratiques de développement moderne :

* **Format PBIP & TMDL** : Versionnage fin du code sous Git, facilitant la collaboration et le suivi des modifications.
* **Principe "Zéro Dette Technique"** : Standardisation des variables DAX, gestion sécurisée des divisions (`DIVIDE`), et élimination des dépendances implicites.
* **Audit & Qualité MCP** : Utilisation de modèles d'IA via le protocole MCP (Model Context Protocol) pour auditer le code DAX, détecter les goulots d'étranglement de performance et valider les bonnes pratiques de modélisation.

---

## 🛠️ Stack Technique

* **Power BI Desktop** (Developer Mode / `.pbip`)
* **VS Code** + Extension TMDL
* **Git & GitHub** (Versionning)
* **DAX & M** (Power Query)
* **MCP / Gemini AI** (Code Review & Audit)