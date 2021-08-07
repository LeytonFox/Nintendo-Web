# Nintendo-Web
**Página web de las sagas de Nintendo**

Super Mario. \
The Legend of Zelda.\
Pokemon. <br />
Metroid.


The action of every agent <br />
  into the world <br />
starts <br />
  from their physical selves. <br />

**Some useful commands**

_Change default branch master to main_\
git config --global init.defaultBranch main

_Create local repository_\
git init (with main branch this time)

_Add files to stage, saved changes_\
git add .
 
_Send to local repository_\
git commit -m "comment"

_Set location to save local repository in cloud_\
git remote add origin 'link repository' (no quotation marks)

_Send all changes to cloud repository with 'main branch' already created in GitHub_\
git push -f origin main

<br />

**others commands**

_see my commits_\
git log --oneline

_see my all commits with more details(actual branch, branches)_\
git log --oneline --decorate --all --graph

_see cloud repository location_\
git remote -v

_Change repository location in cloud_\
git remote set-url origin 'new link repository' (no quotation marks)
