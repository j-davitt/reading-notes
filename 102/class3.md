
# Class 3 notes - Git Intro

Git is the foundation for collaborative work in this field.

## Basic commands

Clone a repo to the current directory by using `git clone` followed by the repo address.
Check file status using `git status`

>- unstaged changes will be red
>- staged changes will be green

1. After editing a file it is flagged as modified
2. Stage the modified file using `git add filename` or stage all changes using `git add .`
3. Commit the staged changes using `git commit -m "description of changes"`
4. Push your changes to git using `git push origin main`

When you are not ready to commit changes but do not want to lose them use `git stash` temporarily hide changes. When you are ready to continue working on the changes use `git stash apply` to retrieve them.


## Things I want to know more about

`git stash`