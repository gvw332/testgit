Assurez-vous d'abord que votre dépôt local est à jour avec le dépôt distant en utilisant => git fetch origin

1 ère étape : Créer une nouvelle branche et switcher directement sur la nouvelle branche => git checkout nomdelabranche

2 ème étape : Une fois que la branche est créée , on peut push sur github => git push origin new-branch
------------------------------------------------------------------------------------------------------------


Imaginons nous modifions la section de la branche (navigation) et on veut le push dans github. 

1: git add .
2: git commit -m "commentaire"
3: git push -u origin main
--------------------------------------------------------------------------------------------------------------
<<<<<<< HEAD
=======


Pour récupérer la branche créée par un autre collaborateur :
git pull origin nomdelabranche

Puis pour publier le commit en local :
git push

Puis pour le fusionner sur la branche main :
git merge logo

>>>>>>> 3aefeaaf0aad52ffad925fab8f1c6ab36108f27e
