# Démographie en Belgique

## Avant-propos

Les consignes sont reprises dans ce document, ainsi que sous forme de commentaires dans les différents fichiers. Elles sont susceptibles d'évoluer. N'hésitez pas à vérifier le lien suivant afin de voir si des modifications n'y ont pas été apportées : https://github.com/BioDataScience-Course/A06Ga_belgium_demo.

## Objecifs

Ce projet est à réaliser en **équipe**. Il s'agit d'un projet **libre**.

Ce projet permet de démontrer l'acquisition des compétences suivantes :

- être autonome face à un nouveau projet
- Comprendre des données à l'aide de métadonnées
- Maîtriser l'importation de données multiformats
- être capable de remodeler des tableaux de données
- Maîtriser la transformation des variables.
- Gérer les types de variables.
- savoir combiner différents tableaux de données
- réaliser des graphiques corrects et intéressants
- interpréter des graphiques 
- Consigner ces observations dans un carnet de notes et puis dans un rapport scientifique.

## Consignes

L’office belge de statistique, Statbel, diffuse des données fiables sur l’économie, la société et le territoire belge.

Pour en apprendre plus sur l’office belge de statistique, vous pouvez
consulter le lien suivant :
<https://statbel.fgov.be/fr/propos-de-statbel>

Vous vous intéressez à la démographie en Belgique. Vous avez à votre disposition des données liées à la densité de population entre 1992 et 2019. 

Dans le dossier data vous pouvez retrouver la densité de population dans 6 fichiers distincts :

- region\_bxl\_ap\_2000.rds : recensement de la population de la région de Bruxelles capitale après les années 2000
- region\_bxl\_av\_2000.rds : recensement de la population de la région de Bruxelles capitale avant les années 2000
- region\_flamande\_ap\_2000.xls : recensement de la population de la Région flamande apres les années 2000
- region\_flamande\_av\_2000.xls : recensement de la population de la Région flamande avant les années 2000
- region\_wallonne\_ap\_2000.csv : recensement de la population de la Région wallonne apres les années 2000
- region\_wallonne\_av\_2000.csv : recensement de la population de la Région wallonne avant les années 2000

Vous devez commencer ce projet par importer et remanier les 6 tableaux de données afin de produire 1 unique tableau de données que vous allez devoir sauvegarder au sein de votre projet. Ces étapes doivent être réalisées dans le script R à votre disposition.

**Note:** N’oubliez pas de commenter votre code afin qu’ils soient
facilement compréhensibles par un collaborateur ou par vous-même dans
plusieurs semaines.

Vous devez ensuite réaliser entre 15 et 20 graphiques ou tableaux résumant l'information sur la démographie en Belgique dans votre carnet de notes. Chaque graphique doit avoir des labels et des unités corrects. Chaque graphique proposé doit être commenté.

Vous devez proposer entre 5 et 6 graphiques/tableaux dans un rapport de synthèse de la démographie en Belgique. Les graphiques ou tableaux doivent provenir de votre carnet de notes.

### Graphiques imposés

Votre carnet de notes (notebook) doit comprendre au minimum les deux graphiques ci-dessous

Vous devez reproduire ce premier graphique dans votre carnet de notes.

![](figure/pop_belge-1.png)

Vous devez reproduire ce second graphique dans votre carnet de notes.

![](figure/pop_belge_sex_region-1.png)


