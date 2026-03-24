# Projet-Data-Visulisation-des-tudiants-entrepreneurs

Création d'une visualisation des données sur les étudiants entrepreneurs.

## Introduction

Pépite Sorbonne Université (Pôle Étudiant Pour l’Innovation, le Transfert et l’Entrepreneuriat) accompagne les porteurs et porteuses de projets de création d’entreprise : mise en réseau avec les acteurs/actrices de l’écosystème (Satt Lutech, PEPITE Factory, association des étudiant(e)s entrepreneur(e)s…), aménagement de cursus, accès à un espace de travail partagé dans l’incubateur Agoranov, soutien pour candidater à des concours dédiés. Il délivre le statut national d'étudiant entrepreneur(SNEE) à l'issue d'un comité d'engagement. 

Lors de mon Service Civique à Pépite Sorbonne Université, j'ai développé par ma proposition un outil de visualisation des données sur les étudiants entrepreneurs. En parallèle j'étais étudiant en Licence 1 Portail Maths Info à l'Université Paris cité.

## Objectif
Chaque année Pépite remonte le nombre d'étudiants entrepreneurs et d'autres statistiques au Ministère de l'Enseignement et Supérieur de la Recherche. Le financement de cette structure dépend du nombre d'étudiants entrepreneurs. Ces statistiques sont consultés de façon récurrentes par l'équipe pour amener à bien sa mission d'accompagnement des étudiants entrepreneurs. Ces statistiques permettent aussi de déterminer la stratégie de sensiblisation de Pépite, dont mon tuteur est le responsable. 

Les statistiques étaient jusque là consulté par un tableau Excel. Cependant, celui-ci avait des soucis de standardisation entre chaque année, parfois une colonne avec des informations en plus pouvait s'ajouter et le tableau devait être remanier. 

## Qualité des données
Les données sont récupérés à partir du site officiel : https://snee.enseignementsup-recherche.gouv.fr/fr/ sous format xls pour Excel. Les données sont remplies par les étudiants lors de leur inscription. Elle peut contenir des doublons ou des étudiants qui ne sont pas ou plus étudiants entrepreneurs. Ces données sont gérés " à la main " sur Excel étant donné que ce sont des cas rares et connue seulement par l'équipe qui font aussi le comité d'engagement et qui délibère oui ou non le statut SNEE.
Etant donné que les informations sont remplies par les étudiants, je les considère fiables. Les informations sont aussi standardisé car les étudiants choississent une information parmi une liste déroulante. Elles permettent de créer un code robuste.

## Structure des données
Le fichier Excel clean est ensuite transformé par pandas en un DataFrame. Elle comporte pleins de colonnes dont celles qui nous intéresse sont : Genre, date de dépot de candidature, Faculté, statut SNEE(oui,non, en attente), Niveau(Licence, Master, Doctorat), secteur.
Pour chaque graphique on crée un nouveau DataFrame qui nous permettra de faire plus facilement des graphes et pour transformer en un sheet pour Excel.

# Seaborn VS matplotlib
Visualisation
# StackOverflow et ChatGPT

# Workflow
Avec les screens pédagogie permettre à l'équipe d'utiliser
# data storytelling
# Auto-Critique et direction d'amélioration
Streamlit, amélioration algorithmiques pour une meilleure efficacité, data 
