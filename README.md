
# Projet d'Analyse du Rendement Locatif en Occitanie

Bienvenue dans le projet Rendement Locatif Occitanie ! Ce projet vise à analyser et visualiser les rendements locatifs dans la région Occitanie. Les données sont transformées à l'aide de Python et visualisées avec JasperReports sous forme de tableaux, graphiques en barres, et diagrammes circulaires.

## Architecture

Le projet se compose des éléments suivants :

Scripts Python : Gèrent la collecte, le nettoyage, la transformation des données brutes et leur exportation pour l'analyse.
JasperReports : Utilisé pour créer des visualisations et des rapports à partir des données transformées.
Données Open Data : Sources de données utilisées pour l'analyse, telles que les transactions immobilières (DVF) et les statistiques INSEE.
Prérequis
Python 3.x : Pour exécuter les scripts de transformation de données.
JasperSoft Studio : Pour éditer et exécuter les rapports JasperReports.
Pandas et autres bibliothèques Python nécessaires (voir requirements.txt).
Installation
Cloner le dépôt
bash
Copier le code
git clone https://github.com/HamzaBenalia/Jasper_Report_RendementLoc_Occitanie



## Ouvrez JasperSoft Studio.
Importez les fichiers .jrxml situés dans le dossier jasper/.
Générez les rapports sous forme de PDF ou d'autres formats souhaités.
Tester les Visualisations
Tableau des Rendements Locatifs
Accédez au tableau des rendements locatifs par département et ville en générant le rapport correspondant dans JasperReports.

## Graphiques et Diagrammes
Graphiques en Barres : Comparaison des rendements locatifs entre différents départements.
Diagrammes Circulaires : Répartition des types de biens immobiliers selon le rendement locatif.
Accéder aux Fichiers Exportés
Les rapports générés peuvent être trouvés dans le dossier outputs/ après exportation depuis JasperSoft Studio.
les PDF généres sont également dans le fichier pdf_Report
