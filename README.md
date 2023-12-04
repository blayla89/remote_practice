# GitHub README Practice 

Purpose: to practice concepts from Launch School's Git/GitHub book in order to soldify a basic conceptual and procedural understanding of a git/github workflow using markdown 

### Git/GitHub Workflow 

*rule of thumb: work local, push remote*

1. create a local project directory in the CLI: `mkdir folderName`
2. create a local git repository: `git init`
   1. make sure to issue the command WITHIN the directory you wish to convert
4. add conventional files: `touch fileName(s)`
   1. *README.md, LICENSE.md, .gitignore*
5. write content to files: `echo "content" > fileName` or use preferred text editor
6. review, stage and commit changes: `git status`, `git add`, `git commit`
7. create a new repository on github with a unique, descriptive name
    1.  do not add files via github => already exist locally and adding would lead to conflicting versions of the files 
8. link local and remote repositories with `git remote add origin url`
9. make sure branch names match: `git branch -M main`
10. update remote with local files AND set default upstream branch: `git push -u origin main`
11. fetch, diff, and pull commits down to the local 
     1. `git fetch`
     2. `git diff [unchanged] [changed]`
     3. `git pull --ff-only`
        1. *can issue `git pull --ff-only` if 100% sure you want to merge the commits*
    

