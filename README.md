---
created: 2022-04-29T16:20:35 (UTC +02:00)
tags: []
source: https://simplonline.co/briefs/659f7490-31bc-4506-b627-b4d84941dccf
author: 
---

![](https://simplonline.co/_next/image?url=https%3A%2F%2Fsimplonline-v3-prod.s3.eu-west-3.amazonaws.com%2Fmedia%2Fimage%2Fjpg%2F54f14e96-e713-4b2a-9900-18a536c12077.jpg&w=1280&q=75)

# Un tableau de bord sur la Covid

Utiliser un conteneur Grafana, grâce à Docker, pour faire de la Dataviz.

## Contexte du projet

Afin de préparer une stack facilement déployable pour l'équipe de dev, les analystes data et le client, votre chef de projet vous demande de préparer des conteneurs pour des outils de Dataviz.

Après discution avec la haute autorité de santé, votre client, les technologies retenues sont MySQL et GRAFANA.

Le serveur est en Linux.

## Modalités pédagogiques

Vous avez 2 jours pour préparer les conteneurs et le dashborad qui affichera au moins 2 graph obtenus à partir de la base de donnée MySQL, dans laquelle 

vous aurez intégré les données sur la vacination mondial du COVID-19.

Le travail se fait en binôme.

Vous devez tester vos conteneurs dans un environnement Linux, soit sur un OS, soit sur WSL.

Avant de réaliser votre capture d'écran, vous présenterez vos travaux au formateur pour qu'il valide le dashboard.

## Critères de performance

- Les conteneurs doivent tourner sur Linux.
- Le README doit permettre de reproduire toutes vos manipulations.
- Le dashboard doit contenir au moins 2 graph et vous devez respecter les technologies demandées

## Modalités d'évaluation

Evaluation par le formateur.

## Livrables

Le livrable est un lien vers un dépôt GitHub qui contient, OBLIGATOIREMENT :
- [X] une capture d'écran du dashborad GRAFANA,
- [X] le docker compose de la stack,
- [~] un README très détaillé du travail fait pour obtenir le dashboard (en Markdown)

![Dashboard Grafana](Covid_Dashboard.png)
