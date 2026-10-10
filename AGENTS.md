# Introduction

Ce projet vise à créer un calendrier de l'avent simple dans lequel chaque jour une question à laquelle on peut répondre soit par choix multiples soit via un input.

## Objectif

L'objectif est que des personnes possédant le qr code ou le lien du site puissent se connecter chaque jour pour répondre à une question.

## Features

- Possibilité de mettre des rappels tous les jours
- Possibilité d'intégrer des images, des vidéos, frames youtube etc.
- Possibilité de retourner voir les questions des  jours précédents par exemple jour 3 on peut voir les questions jour 2 et 1 mais pas des jours après.
- 

## Technique

- Le site n'aura besoin que d'un frontend, les questions et leurs réponses seront stockées dans un fichier au format JSON.
- Pour la stack elle sera simple, du React en TS avec aucun framework CSS, le CSS sera natif, pas besoin d'importer Tailwinds pour un petit site.
- Pour les rappels, utiliser l'application agenda du téléphone si possible

## UserFlow

### Premier Persona

La personne arrive sur le site via un QR Code elle voit la popup qui lui recommande de mettre un rappel pour répondre aux questions, elle clique dessus et sélectionne Google Agenda, elle arrive sur l'appli et tout est enregistré automatiquement, elle lit la question, sélectionne sa réponse et confirme, ensuite le site confirme sa bonne réponse, la félicite et l'invite à attendre demain ou à voir les questions des jours précédents s'il y en a.

### Second Persona

La personne arrive sur le site avec le lien, elle visionne une vidéo et lit la question puis choisis sa réponse, elle confirme sa réponse et le site lui dit que c'est une mauvaise réponse et qu'elle peut réessayer, elle essaie de resélectionner sa réponse précédente mais ne peut pas car le développeur du site l'a bloqué ce GOAT et donc sélectionne une autre réponse, la réponse est correcte le site l'invite à attendre demain ou à voir les questions des jours précédents.
