# Job-Board *VITE-FAIT*

Le projet avait pour but de réaliser un Job-Board (comme Indeed, Trabajo etc...) en binome dans le cadre du projet concluant la piscine de Web de Pré-Msc au sein de l'école EPITECH. Le site Web devant être dynamique et intéractif en créant une API (avec flask) reliant la partie front-end (avec VueJS) et la base de données (SQL). 

## Pour commencer (Ubuntu)

### Pré-requis

Ce qu'il est requis pour commencer le projet...

- MySQL & Phpmyadmin
- Flask
- VueJS

### Installation

Les étapes pour installer les packages....

BDD : ( compte phpmyadmin => utilisateur = phpmyadmin & mot de passe = root)

- Importer la base de données avec le script SQL ``JobBoard.sql``

Flask : 

- Se rendre dans  ``/back/api``, installer les modules nécessaires avec la commande ``pip install modules.txt``
- Puis lancer le serveur Flask avec la commande ``flask --app main run``

VueJS : 

- Dans ``/job-board-front``, éxecutez la commande ``npm install`` pour installer toutes les dépendances
- Puis lancer le serveur avec la commande ``npm run dev`` et faites un ctrl + click sur l'url ``localhost``

Vous devriez vous trouver sur notre site ! 
 
## Démarrage

Vous pouvez vous connecter au site avec n'importe quel compte présent dans la base de données avec le mot de passe ``root``.
Liste des adresses email : 
- ut.quam@outlook.couk
- mauris@hotmail.couk
- mi.duis@outlook.com
- dui.augue@outlook.net
- libero.morbi@google.edu

## Fabriqué avec

* [VueJS](https://vuejs.org/) - Framework Front-end
	- * [Bootstrap](https://getbootstrap.com/) - Framework CSS (front-end)
* [Flask](https://flask.palletsprojects.com/en/2.2.x/) - MicroFramework de vév Web en python
* [SQL](https://sql.sh/) - Language de BDD 
	- * [SQLAlchemy] (https://www.sqlalchemy.org/) - BDD toolkit pour python

## Auteurs

* **Hugo Vincent** _alias_ [@Hy0g0](https://github.com/Hy0g0)
* **Mehdi Fessiane** _alias_ [@Mehdi-fsn](https://gist.github.com/Mehdi-fsn)


