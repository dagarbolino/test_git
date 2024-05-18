# Testing git

git init -> Pour initialiser le projet
git status -> Permet de voir l'état du projet
git add . -> Ajoute tous les fichiers
git add ...le fichier... -> le fichier sélectionné
git commit -m "Message de description du commit"
git push -u origin   puis le nom de la branch -> 


git log --oneline  -> Pour voir l'historique




## Pour la création d'une branch
git checkout -b   puis le nom de cette branch -> la branch est créée et nous sommes sur cette branch
git branch -> nous permet de voir les branch de créé
git branch -d    puis le nom de la branch  -> pour la delete

git checkout  puis le npm de la branch  -> pour changer de branch



git checkout -b branch3
git status -> exemple : READEME.md en rouge
git add README.md
git status -> le README.md en vert
git commit -m "new commit in branch3"

git push -u origin branch3 -> pour le push vers le github

## Nous allons sur le github
    1. Click sur Compare & pull request
    2. Ajouter une description à ce code qui est publié sur cette branch
    3. Click Create pull request
    4. Click Merge pull request, and add comment
    5. Click Confirm merge 
    6. And If Delete branch Click


## return in terminal
    1. git branch main
    2. git branch -d branch3