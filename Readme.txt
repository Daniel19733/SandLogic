How to configure to remote repository:

git config --list
git config user.name "Daniel19733"
git config user.email "daniel.bollavarapu@cyient.com"


git config --global user.name "Daniel19733"
git config --global user.email "daniel.bollavarapu@cyient.com"

git init -> to create local repository 
git add . -> to add files and folder to local repository 
git status -> to verify whether the files and folder saved or not
git commit -m "Test Code Commit 1" -> to commit perminently 
git status -> to check working tree clean
git branch -> to check the current branch 
git remote -v -> to check in which remote repo we are connected 

git remote add orign "https://github.com/IP-CyientProjects/Lidar-Editing-Platform-Repo.git"

git status 
git add .
git commit -m "readme.txt modified"
git status
git log
git push --force orign master
