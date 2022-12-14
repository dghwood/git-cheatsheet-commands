# Git & Github CheatSheet

## Setup Git

- `git config --global user.email "you@example.com"`
- `git config --global user.name "Your Name"`

## Setup GitHub 

- `gh auth login` 

## Create a GitHub repo 

- `gh repo create`
    - This can clone the repo locally, and will set your git remote orgin
- `git remote -v`
    - This will list your remote origins on github 

## Add files & commit 

- `gh add <files>`

- `gh commit -m "<message>"`

- Alternatively you can simplify to `gh commit -a -m "<message>"`

## Push to Repo 

- `gh push -u origin <branch name>`
    - Note: the `-u` means next time you can just do `gh push`
    - Note: if you want to change the branch name use `git branch -M <new name>`

## Delete local 

- Just delete the directory (including the .git folder) 

## Start from scratch 

- `git clone <github url>`
    - this will create a git folder called `<repo name>` 
