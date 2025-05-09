# twilio-sms-api

Ce projet permet d'envoyer des SMS avec Twilio en utilisant PHP et Render.

## Déploiement

- Déposez ce repo sur GitHub
- Créez un Web Service sur https://render.com
- Ajoutez ces variables d'environnement :
  - TWILIO_SID
  - TWILIO_TOKEN
  - TWILIO_NUMBER

## Appel API

POST /sms_sender.php

Body JSON :
{
  "to": "+228XXXXXXXX",
  "message": "Votre message ici"
}
