Assurez-vous d'abord que votre dépôt local est à jour avec le dépôt distant en utilisant => git fetch origin

1 ère étape : Créer une nouvelle branche et switcher directement sur la nouvelle branche => git checkout nomdelabranche

2 ème étape : Une fois que la branche est créée , on peut push sur github => git push origin new-branch
------------------------------------------------------------------------------------------------------------


Imaginons nous modifions la section de la branche (navigation) et on veut le push dans github. 

1: git add .
2: git commit -m "commentaire"
3: git push -u origin main
--------------------------------------------------------------------------------------------------------------