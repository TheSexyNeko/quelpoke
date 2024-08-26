# Quelpoke : Documentation

## Description:
L'application permet a l'utilisateur de pouvoir trouver quel pokemon corréspond a son prénom.

## Fonctionnement général:
Le prénom est transformer par calcule la somme sha1 du nom et renvoie le modulo qui sera l'ID des pokemon allant de 1 à 151.

## Comment lancer le service sur son poste:
Pour pouvoir tester, il faut commencer par :

1. Cloner l'application via github.
2. Ensuite il faut [télécharger Golang]("https://go.dev/dl/go1.23.0.windows-amd64.msi")
3. Une fois Golang installé, il faut lancer un powershell puis effectuer les commandes suivantes : 

    ```$ cd CHEMIN_DU_DOSSIER_DEZIP```

    ```$ go build .\main.go```

4. ensuite il faut aller dans le dossier puis executer le main.exe
5. Cela va ouvrir un terminal
6. Ensuite il faut aller sur un navigateur et ecrire localhost:8080 dans la barre de recherche
7. Si tout est bon l'application est lancée.