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

- `gh push origin main`