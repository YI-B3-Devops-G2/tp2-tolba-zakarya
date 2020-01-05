# B3 Devops - TP 2
## Info
- mail: zakarya.tolba@ynov.com
- github_username: zaktolba

----

### Projet
- Le projet consiste à découvrir l'utilisation de Docker avec l'installation et la configuration d'un projet API simple.

 ### Pré-requis
 * Docker 🐳
 * Node.js 💚
 

 ### Installation
1) Cloner le repo sur votre PC et ouvrez un terminal de commande.
2) Positionnez vous dans le répertoire `tp2-tolba-zakarya\` et saisissez la commande:

```npm install```

3) Positionnez vous dans le dossier `tp2-tolba-zakarya\docker` et saisissez la commande:

```docker-compose build && docker-compose up```


3) Le projet est désormais installé et démarré 😎

### Fonctionnement
Le site est accessible avec l'URL http://localhost:8080/
La première page devrait afficher le contenu suivant:
```
Welcome on Nginx
```

Pour vérifier si l'API fonctionne, naviguez sur https://localhost:8080/api, le site devrait afficher le contenu suivant:

```
{"message":"Hello World !"}
```

https://localhost:8080/status devrait afficher le contenu suivant:
```
{"status": "OK", "postgresUptime": String, "redisConnectedClients": Number}
```

### Arrêt/Démarrage du projet

Pour **fermer** le projet docker:

* Positionnez vous dans le dossier `tp2-tolba-zakarya\docker` et saissisez la commande suivante:

```docker-compose down```

* Il suffiras de saisir ```docker-compose up``` à l'intérieur du répertoire pour **démarrer** de nouveau le projet
