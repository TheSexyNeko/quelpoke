# Quelpoke : Documentation

## Description:
L'application permet a l'utilisateur de pouvoir trouver quel pokemon corréspond a son prénom.

## Fonctionnement général:
Le prénom est transformer par calcule la somme sha1 du nom et renvoie le modulo qui sera l'ID des pokemon allant de 1 à 151.

## Comment lancer le service sur son poste:
Pour pouvoir tester, il faut commencer par :

1. Cloner l'application via github.
2. Ensuite il faut [télécharger Docker]("https://www.docker.com/products/docker-desktop/")
3. Une fois Docker installé, il faut lancer un powershell puis effectuer les commandes suivantes : 

    ```$ docker build -t quelpoke . ```

    ```$ docker run -p 8080:8080 quelpoke```

4. Ensuite il faut aller sur un navigateur et ecrire localhost:8080 dans la barre de recherche
5. Si tout est bon l'application est lancée.