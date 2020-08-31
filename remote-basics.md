## Remote



## clone.
  `git clone <remote-git-url>`
  Download the remote reposioty in my local machine.
 - create a directory with the name of remote repo.
 - cd into that dir
 - git init. Initialize an empty repo in that dir.
 - add a remote  <remote-git-url> and names it origin.
 - git pull.

# git push
  git push origin <branch_name>


# git fetch
  Download the latest changes from remote repo and into your local repo ina branch named  remotes/origin/<branch_name>
  `git fetch origin <branch_name>`
# git pull
  git fetch + git merge
  `git pull origin <branch_name>`


# trackign

while creating a branch

`git checkout --track origin/<branch_name>`
 or

if branch already exit
`git branch -u origin/<branch_name>`

while pulling or pushing
`git push -u origin <branch_name>`
