🏨 Azur Palace | Worldwide 5-Star Hotel Performance
Macro-level insights into group health and guest satisfaction — Un projet Power BI avancé de pilotage hôtelier international, développé au format PBIP (Power BI Project), structuré en architecture en étoile et audité via l'intelligence artificielle (Protocoles MCP).

📌 Vue d'ensemble
Le projet Azur Palace a pour objectif d'analyser la performance globale d'un groupe hôtelier 5 étoiles à l'échelle internationale. Il croise les données de satisfaction client (Guest Voice) avec les indicateurs macro-économiques et géographiques pour fournir aux décideurs une vision 360° de la santé des établissements et de la qualité de service.

🏗️ Architecture & Modélisation des Données
Le modèle sémantique repose sur une architecture en étoile (Star Schema) rigoureuse, optimisée pour les performances du moteur VertiPaq :

FACT_Reviews : Table de faits centralisant les évaluations, scores de satisfaction par catégorie et retours clients.

DIM_hotel : Référentiel des établissements (localisation, région, caractéristiques 5 étoiles).

DIM_users : Segmentation et typologie des clients / répondants.

DIM_Date : Calendrier complet gérant la Time Intelligence.

Radar Hotels : Tableaux virtuels et mesures pour l'analyse multicritère (Spider/Radar Charts).

📊 Périmètre Fonctionnel & Mesures DAX
Les mesures DAX sont structurées par dossiers d'affichage (Display Folders) :

Summary & KPI Globaux : Score médian global, nombre total d'avis, pourcentage d'hôtels au-dessus de la médiane.

Customer Voice (CX) : Analyse détaillée des axes de satisfaction (Propreté, Emplacement, Confort, Personnel, Rapport Qualité/Prix) comparés aux attentes de la marque.

Macro Performance : Suivi géographique et temporel (cartes interactives, filtres dynamiques par région, année et trimestre).

🤖 Gouvernance & Audit IA via MCP (Model Context Protocol)
Dans une démarche de Data Engineering moderne, ce projet intègre une procédure d'audit automatisée via l'intelligence artificielle sous VS Code :

Exploitation du format PBIP / TMDL : Analyse directe de la structure textuelle du modèle pour valider les relations et la syntaxe DAX.

Optimisation des performances : Sécurisation des calculs avec la fonction DIVIDE, gestion des valeurs nulles avec COALESCE, et privilège accordé aux variables (VAR ... RETURN) pour alléger la charge CPU.

Zéro Dette Technique : Standardisation du typage des mesures et injection de descriptions métier pour une meilleure autonomie des utilisateurs finaux.

🚀 Stack Technique
Outil de restitution : Power BI Desktop (Format source : .pbip)

IDE & Versionning : VS Code, Git / GitHub

Langages / Formats : DAX, TMDL, JSON

Méthodologie : Star Schema, Audit IA automatisé (MCP)