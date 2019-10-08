## Exercices Entretiens techniques JS


Les exercice doivent être réalisés avec le niveau de qualité attendu 
- dans les pratiques
- en tant que code de production.

Le temps approximatif nécessaire à la réalisation de chaque groupe d'exercice est de 2 heures.
Le candidat choisit librement son groupe d'exercices (Frontend, fullstack ou backend) en fonction de ce qu'il estime être le plus pertinent.

----------------------------
### Repositories

Les repos suivants peuvent être forkés dans le repo github du candidat :

https://www.github.com/SebQuenet/react-training-front

https://www.github.com/SebQuenet/react-training-back

----------------------------
### Lancement de l'application (après installation des packages)

#### Lancer le frontend
```bash
cd react-training-front
yarn start
```

#### Lancer le serveur
```bash
cd react-training-back
yarn json:server
```

#### Lancer le backend
```bash
cd react-training-back
yarn start
```

----------------------------
### Connexion

* On peut se logguer à l'application avec l'un des couples de login / mdp suivant : 
  * jon.snow@thewall.ws / password
  * arya.stark@braavos.es / password
  * the.hound@lannisport.ws / password
  * samwell.tarly@thereach.ws / password

Les repos de l'application contiennent des libs utilitaires suffisament versatiles pour que le candidat s'y retrouve mais celui-ci peut évidemment y ajouter les libs qu'il a l'habitude d'utiliser

--------------------------
### Exercice développeur front
- En conservant le layout côté front, faire une application qui permet de :
* récupérer les informations d'un livre et les afficher
* récupérer les informations de l'ensemble des personnages d'un livre et les afficher

--------------------------
### Exercice développeur fullstack
- L'application possède un système d'authenficiation basique, et sans sauvegarde de session
* Faire un systeme qui gère Oauth2 côté backend
* Côté front, la session devra être persistante (un rafraichissement d'une page devra gardé les informations sur l'utilisateur loggué).

------------------------------
### Exercice développeur backend
- On utilise actuelement json-server pour stocker les données
* Migrer l'application vers mongodb (en utilisant par exemple mlab) ou vers postgresql, au choix du développeur.
* Ajouter un document ou une table commentaires qui doit contenir les commentaires éventuels des utilisateurs
* Faire les routes permettant :
  * D'ajouter un commentaire pour l'utilisateur loggué
  * De supprimer un commentaire qui appartient à l'utilisateur loggué
  * D'afficher la liste des commentaires d'un utilisateur loggué
