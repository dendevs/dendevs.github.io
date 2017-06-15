---
layout: default
title: MoneyCheck
categories: projet-code
---
# MoneyCheck

*Petit visuel des dépenses financières*

## Besoins

* Lister toute les dépenses mensuelle.

* Identifier le type de dépenses.

* Connaitre le total des dépenses sur un durée de temps pour une catégorie.

* Identifier les dépenses qui sont annuelles.

## Analyse

### Ajout

En tant qu'utilisateur logger je veux pouvoir ajouter une dépense dans le mois courant.  
Une dépense est un montant avec virgule positif ou négatif associé à une categorie.  

Une categories se découpe en plusieur niveau du général au spécifique.  
ex: 

* Loyers

* Hobbies -> potager

* Hobbies -> Bricolage -> Hubo

Une note explicative peut etre ajouter avec la dépense ainsi qu'un élément permettant d'identifier la dépense comme étant annuelle.

![Use case ajout](/assets/moneycheck/mck-usecase-ajout.png "Ajout")

## Technologies et outils

[meteorjs](https://www.meteor.com/)

[mongodb](https://docs.mongodb.com/manual/introduction/)

## RMQ

!Attention à la confusion qu'induit le terme dépense. J'ajoute une dépense, j'ai une dépense en plus c'est donc un -.
transaction plutot que dépense ?
