## Installation de Git
Si vous ne l'avez pas déjà installé, téléchargez et installez Git depuis le [site officiel](https://git-scm.com).

## Initialiser Git
1. Utilisez la commande suivante pour initialiser Git :
    ```bash
    git init
    git remote add origin https://github.com/gvw332/testgit.git
    git status
    ```

## Assurez-vous d'abord que votre dépôt local est à jour
2. Utilisez la commande suivante pour récupérer les dernières modifications du dépôt distant :
    ```bash
    git fetch origin
    ```

## Créer une nouvelle branche et switcher directement sur la nouvelle branche 
    ```bash
    git branch nomdelabranche
    git checkout nomdelabranche
    ```

## Une fois que la branche est créée et qu'on a bien été switché dans la nouvelle branche , on peut push sur github 
    ```bash
    git push origin nomdelabranche
    ```

## Imaginons que je veuille modifier mon code, je me met dans la bonne branche et ensuite : 
    ```bash
    git add nomdufichiermodifié.html
    git commit -m "commentaire"
    git push -u origin navigation
    ```

## Pour récupérer la branche créée par un autre collaborateur :
    ```bash
    git pull origin nomdelabranche
    git push
    git merge log
    ```

## Imaginons que je veuille vérifier si mes collaborateurs ont publié des mises à jour:
    ```bash
    git pull
    ```


## Pour publier ensuite ses modifications : 

    ```bash
    git status
    git add nomdufichier
    git commit -m "commentaire"
    git push
    ```
(
1: Vérifier avec un " git status " les fichiers à modifier.
2: Un par un les ajouter et les commit " git add nomdufichier " et ensuite " git commit -m "commentaire" ".
3: Terminer par un " git push ".
)

