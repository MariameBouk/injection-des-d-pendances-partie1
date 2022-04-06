Cette partie concerne l'injection des dépendances par instanciation statique ce qui implique un couplage fort.

![image](https://user-images.githubusercontent.com/101976300/161955346-ac140624-640f-4112-a054-08835b694511.png)


Cette partie concerne une injection dynamique des dépendances par invocation d'un fichier(config.txt) ce qui permet d'obtenir les noms des classes dont on a besoin sans toucher le code, et c'est à Class.forName de récuperer les classes.

![image](https://user-images.githubusercontent.com/101976300/161957591-82bb0f7b-acf0-4abe-a35d-03235af6f48e.png)


