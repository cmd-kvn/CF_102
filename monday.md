# monday

//after creating a repository on gitHub, "clone or download" and "clone with https". Then, copy the url and use:
git clone __url__
//in git bash

//then:
cd _folder_
//the folder is created after the clone.

touch fileName.md
//creates an md file in the folder

git add fileName.md
//tells git to start tracking with version control

git commit -m "comments"
//tracks version control for fileName.md

git add -p
//after you make changes to fileName.md and save them, "git add-p", p for patches, lets you control what new content is added to the file on gitHub.

//you still need to push all the changes and new creations to gitHub
git push origin master
