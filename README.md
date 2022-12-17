# setting-up-a-new-repo


…or create a new repository on the command line

    echo "# setting-up-a-new-repo" >> README.md
    git init
    git add README.md
    git commit -m "first commit"
    git branch -M main
    git remote add origin https://github.com/exseuit/setting-up-a-new-repo.git
    git push -u origin main

…or push an existing repository from the command line

    git remote add origin https://github.com/exseuit/setting-up-a-new-repo.git
    git branch -M main
    git push -u origin main

…or import code from another repository

You can initialize this repository with code from a Subversion, Mercurial, or TFS project.





## Authorise GitHub CLI

        gh auth login
        gh repo create my-newrepo --public --source=. --remote=upstream --push

gh repo create:  https://cli.github.com/manual/gh_repo_create


### What is GitHub CLI for?

The GitHub command line (CLI) tool can be used to carry out tasks relating to pull requests, issues and other GitHub tasks to your terminal.  Meaning if you are working with code within your terminal and need to carry out a task with GitHub you don't have to leave that terminal session.

Each command starts with gh. 
