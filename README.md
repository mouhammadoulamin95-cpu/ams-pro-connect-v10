# AMS Pro Connect V10 — Online

Version construite pour le vrai échange Client ↔ AMS Pro.

## Fonctionnement
- Le client crée son compte ou se connecte.
- AMS Pro se connecte avec le compte administrateur.
- Les conversations sont enregistrées dans une base SQLite côté serveur.
- Les messages sont transmis en temps réel avec Socket.IO.
- Le client et AMS Pro ne partagent donc plus seulement le stockage local du navigateur.

## Compte administrateur de démonstration
Téléphone : +237680296346
Mot de passe : 1234

## Lancer
Installer Node.js puis :
`npm install`
`npm start`

Ouvrir ensuite `http://localhost:3000`.

## Important
Cette version est une vraie base full-stack, mais elle n'est pas encore hébergée publiquement. Pour l'envoyer à un client sous forme de lien, il faut déployer ce dossier sur un serveur HTTPS et conserver la base de données sur ce serveur.
