# 📊 Analyse et Visualisation des Données : Étudiants-Entrepreneurs (Pépite SU)

## 🌟 Introduction
Le **Pépite Sorbonne Université** (Pôle Étudiant Pour l’Innovation, le Transfert et l’Entrepreneuriat) accompagne les porteurs de projets de création d'entreprise. Il offre un écosystème complet : mise en réseau, aménagement de cursus et délivrance du **Statut National d’Étudiant-Entrepreneur (SNEE)**.

Dans le cadre de mon **Service Civique** au sein de cette structure, et parallèlement à ma Licence 1 (Maths-Info), j'ai pris l'initiative de concevoir un outil de visualisation de données pour transformer des fichiers bruts en indicateurs stratégiques.

---

## 🎯 Contexte et Objectifs
Le financement et la stratégie de sensibilisation du Pépite dépendent directement des statistiques remontées au Ministère de l’Enseignement Supérieur et de la Recherche.

* **Le problème :** Les données étaient gérées via des tableaux Excel manquant de standardisation, rendant l'analyse chronophage.
* **La solution :** Développer un programme automatisé pour éclairer les décisions de l'équipe et optimiser la stratégie de sensibilisation.

---

## 🛠️ Stack Technique
### **Data Processing**
* **Python / Pandas :** Nettoyage des données, gestion des doublons et transformation des fichiers `.xls` en DataFrames exploitables.

### **Data Visualization**
* **Seaborn :** Utilisé pour sa syntaxe intuitive et son intégration native avec Pandas.
* **Matplotlib :** Utilisé pour la gestion avancée des mises en page (*subplots*) et la personnalisation fine des graphiques.

---

## 📈 Qualité et Traitement des Données
Les données proviennent de la plateforme officielle SNEE.

### **Fiabilité**
Les informations sont saisies par les étudiants via des listes déroulantes, assurant une bonne standardisation dès la source.

### **Nettoyage**
* Suppression des doublons.
* Filtrage des statuts (Oui / Non / En attente).
* Gestion des cas particuliers identifiés par l'équipe pédagogique.

---

## 💡 Data Storytelling & Insights
> L'analyse technique ne suffit pas sans la compréhension du terrain.

### **1. Flux des candidatures**
<img width="1091" height="563" alt="Nbre candidature dans l'année" src="https://github.com/user-attachments/assets/56cfe16b-82be-40cf-a92e-c94d7cef6a6d" />

**Note :** Le pic observé en juin (06-2022) s'explique par le report des dossiers non traités de l'année précédente sur le nouveau cycle de candidature.

### **2. Répartition par Genre et Faculté**
<img width="2008" height="957" alt="Répartition FACUlté bar" src="https://github.com/user-attachments/assets/fed8f925-9bb1-4942-b42a-e62857146a0c" />

* **Observation :** Forte présence des étudiants de la **FSI** (Faculté des Sciences et Ingénierie), où la culture entrepreneuriale est très ancrée.
* **Analyse critique :** En Faculté de Santé, malgré une majorité de femmes dans les effectifs globaux, les postulants SNEE sont majoritairement des hommes. Cela a permis à l'équipe d'identifier des axes de sensibilisation ciblés.

**Légende des acronymes :**
* **Alliance :
