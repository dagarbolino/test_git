# Cheat Sheet git

## Main command 

    1. git init -> To initialize the project
    2. git status -> Allows you to see the status of the project
    3. git add . -> Add all files
    4. git add + the file... -> The selected file
    5. git commit -m "Commit description message"
    6. git push -u origin + Then the name of the branch
    7. git log --oneline  -> To view history


## For creating a branch

    1. git checkout -b + Then the name of this branch -> The branch is created and we are on this branch
    2. git branch -> Allows us to see the branches created
    3. git branch -d  + Then the name of the branch -> to delete it
    4. git checkout + then the npm of the branch -> To change branch
    5. git checkout -b branch3
    6. git status -> example : The READEME.md in red
    7. git add README.md
    8. git status -> The README.md in green
    9. git commit -m "new commit in branch3"
    10. git push -u origin branch3 -> For push to github


## Let's go to github

    1. Click for Compare & pull request
    2. Add a description to this code that is published on this branch
    3. Click Create pull request
    4. Click Merge pull request, and add comment
    5. Click Confirm merge 
    6. And If Delete branch Click


## return in terminal
    1. git checkout main -> To be on the main branch
    2. git branch -d branch3 -> To delete this branch
    3. git pull -> To return the code