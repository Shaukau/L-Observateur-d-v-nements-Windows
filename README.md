# L-Observateur-d-v-nements-Windows

# DNS Monitoring - Event Viewer

## Objectif

Cette vue personnalisée permet de surveiller les événements liés au serveur DNS sous Windows Server.

## Niveaux surveillés

* Critique
* Erreur
* Avertissement
* Information

## Sources surveillées

* DNS-Server
* DNS-Server-Service
* 
![https://github.com/Shaukau/L-Observateur-d-v-nements-Windows/blob/main/Capture%20d'%C3%A9cran%202026-05-30%20104959.png](https://github.com/Shaukau/L-Observateur-d-v-nements-Windows/blob/main/Capture%20d'%C3%A9cran%202026-05-30%20104959.png)

![https://github.com/Shaukau/L-Observateur-d-v-nements-Windows/blob/main/Capture%20d'%C3%A9cran%202026-05-30%20104925.png](https://github.com/Shaukau/L-Observateur-d-v-nements-Windows/blob/main/Capture%20d'%C3%A9cran%202026-05-30%20104925.png)


## IDs d'événements surveillés

| ID   | Description                     |
| ---- | ------------------------------- |
| 2    | Démarrage du serveur DNS        |
| 4    | Arrêt du serveur DNS            |
| 409  | Erreur de résolution de nom     |
| 501  | Échec de chargement de zone DNS |
| 502  | Échec de chargement de zone DNS |
| 6001 | Problème de réplication DNS     |
| 6002 | Problème de réplication DNS     |

## Résultat

Cette vue permet d'identifier rapidement les erreurs, avertissements et événements importants liés au fonctionnement du service DNS.


