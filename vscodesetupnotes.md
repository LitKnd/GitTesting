# Install Git 

https://git-scm.com/downloads

Or use a package manager

On windows, I like Chocolatey
    choco install git
    choco upgrade git


# Configure global Git preferences

git config --global user.email name@domain.com
git config --global user.name "First Last"


# Set VSCode as the default git commit / diff tool

git config --global core.editor "code --wait"

# Set VSCode as the default merge tool: 

git config --global merge.tool vscode
git config --global mergetool.vscode.cmd "code --wait $MERGED"

# VsCode Git Settings

Git: Autofetch

# Extensions 

Git Cheatsheet extension

PowerShell extension

Install posh-git - https://github.com/dahlbyk/posh-git#installation 

* notepad $PROFILE
* Import-Module posh-git

GitLens extension
