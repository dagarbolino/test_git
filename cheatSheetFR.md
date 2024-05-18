# Fiche memo utilisation de git

## Commande principale 

    1. git init -> Pour initialiser le projet
    2. git status -> Permet de voir l'état du projet
    3. git add . -> Ajoute tous les fichiers
    4. git add + le fichier... -> le fichier sélectionné
    5. git commit -m "Message de description du commit"
    6. git push -u origin + puis le nom de la branch 
    7. git log --oneline -> Pour voir l'historique


## Pour la création d'une branch

    1. git checkout -b + puis le nom de cette branch -> la branch est créée et nous sommes sur cette branch
    2. git branch -> nous permet de voir les branch de créé
    3. git branch -d + puis le nom de la branch  -> pour la delete
    4. git checkout + puis le npm de la branch  -> pour changer de branch
    5. git checkout -b branch3
    6. git status -> exemple : READEME.md en rouge
    7. git add README.md
    8. git status -> le README.md en vert
    9. git commit -m "new commit in branch3"
    10. git push -u origin branch3 -> pour le push vers le github


## Nous allons sur le github

    1. Click sur Compare & pull request
    2. Ajouter une description à ce code qui est publié sur cette branch
    3. Click Create pull request
    4. Click Merge pull request, and add comment
    5. Click Confirm merge 
    6. And If Delete branch Click


## return in terminal
    1. git checkout main -> pour être sur la la branch main
    2. git branch -d branch3 -> pour delete cette branch
    3. git pull -> pour ramener le code