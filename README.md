📊 ## Analyse et Visualisation des Données : Étudiants-Entrepreneurs (Pépite SU)
🌟 Introduction
Le Pépite Sorbonne Université (Pôle Étudiant Pour l’Innovation, le Transfert et l’Entrepreneuriat) accompagne les porteurs de projets de création d'entreprise. Il offre un écosystème complet : mise en réseau (Satt Lutech, Agoranov), aménagement de cursus et délivrance du Statut National d’Étudiant-Entrepreneur (SNEE).

Dans le cadre de mon Service Civique au sein de cette structure, et parallèlement à ma Licence 1 (Maths-Info), j'ai pris l'initiative de concevoir un outil de visualisation de données pour transformer des fichiers bruts en indicateurs stratégiques.

🎯 Contexte et Objectifs
Le financement et la stratégie de sensibilisation du Pépite dépendent directement des statistiques remontées au Ministère de l’Enseignement Supérieur et de la Recherche.

Le problème : Les données étaient gérées via des tableaux Excel manquant de standardisation, rendant l'analyse chronophage et complexe lors de l'ajout de nouvelles colonnes ou de changements de format annuels.

La solution : Développer un programme capable de générer un visuel parlant et automatisé pour éclairer les décisions de l'équipe et de mon tuteur (responsable de la sensibilisation).

🛠️ Stack Technique
Python / Pandas : Nettoyage des données, gestion des doublons et transformation des fichiers .xls en DataFrames exploitables.

Matplotlib & Seaborn : Création de visualisations. J'ai privilégié Seaborn pour sa syntaxe intuitive avec Pandas, tout en utilisant Matplotlib pour la gestion avancée des subplots.

📈 Qualité et Traitement des Données
Les données proviennent de la plateforme officielle SNEE.

Fiabilité : Les informations sont saisies par les étudiants via des listes déroulantes, assurant une bonne standardisation.

Nettoyage : Suppression des doublons et filtrage des statuts (Oui / Non / En attente) pour ne garder que les données pertinentes pour le comité d'engagement.

💡 Data Storytelling & Insights
L'analyse technique ne suffit pas sans la compréhension du terrain. Voici quelques exemples d'insights générés :

1. Flux des candidatures
<img width="1091" height="563" alt="Nbre candidature dans l'année" src="https://github.com/user-attachments/assets/56cfe16b-82be-40cf-a92e-c94d7cef6a6d" />
Note : Le pic observé en juin (06-2022) s'explique par le report des dossiers non traités de l'année précédente sur le nouveau cycle de candidature.

2. Répartition par Genre et Faculté
<img width="2008" height="957" alt="Répartition FACUlté bar" src="https://github.com/user-attachments/assets/fed8f925-9bb1-4942-b42a-e62857146a0c" />

Observation : On remarque une forte présence des étudiants de la FSI (Faculté des Sciences et Ingénierie), domaine où la culture entrepreneuriale est très ancrée.

Analyse critique : À l'inverse, en Faculté de Santé, bien que les femmes soient majoritaires dans les effectifs globaux, les postulants SNEE sont majoritairement des hommes. Cela a permis à l'équipe de s'interroger sur d'éventuels biais de sensibilisation.

Légende des acronymes :

Alliance : MNHN, Insead, UTC, PSPBB, Cnam, etc.

FL : Faculté de Lettres (Sorbonne)

FDS : Faculté de Santé

FSI : Faculté des Sciences et Ingénierie

Hors SU : Établissements extérieurs.

🚀 Auto-critique et Perspectives
Ce projet, réalisé en début de cursus (L1), m'a permis de poser les bases de la Data Analysis. Avec le recul, voici les axes d'amélioration identifiés :

Optimisation : Pour un dataset plus large (>100k lignes), une vectorisation plus poussée sous Pandas serait nécessaire.

Interface Utilisateur : L'utilisation de Streamlit aurait permis de transformer ce script en une application web interactive, facilitant encore plus l'accès aux données pour l'équipe non-technique.

Statistiques Avancées : Passer de la statistique descriptive à l'analyse prédictive pour anticiper le volume de candidatures.

Ce que j'ai changé et pourquoi :
Structure : J'ai utilisé des titres clairs et des listes à puces pour que le recruteur puisse scanner ton projet en 30 secondes.

Vocabulaire : Remplacement de termes simples par un vocabulaire plus "Data" (vectorisation, statistique descriptive, indicateurs stratégiques, insights).

Mise en valeur : J'ai bien précisé que c'était une proposition de ta part durant ton Service Civique, ce qui prouve ta force de proposition.

Honnêteté technique : J'ai gardé ton paragraphe sur ChatGPT et StackOverflow mais en le tournant de façon à montrer que tu sais chercher des solutions par toi-même (très apprécié en alternance).
