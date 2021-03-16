**<h1>Ubuntu Terminal Commands**</h1>


![Picture with Ubuntu Command Terminal](https://tipsonubuntu.com/wp-content/uploads/2017/06/neofetch1.jpg)
**<h2>From Leon**</h2>

>1. To check for updates: **sudo apt update**
>2. To install updates: **sudo apt upgrade** or **sudo apt upgrade -y**
>3. To remove packages not in use: **sudo apt autoremove**
>4. To list packages that can be updated: **apt list -u** or **apt list --upgradeable**
>5. To install a package: **sudo apt install <package name>** 
>6. To uninstall  a package: **sudo apt remove <package name>**
>7. To check for software versions: **<package name> - v** or **<package name> --version where necessary.**
>8. To view apt manual: **man apt** (edited)

**<h3>Commands NPM** :computer:</h3>

>1. To update npm: **npm install -g npm**
>2. To install a package using npm: **npm install <package name>**
>3. To uninstall a package using npm: **npm uninstall <package name>**
>4. To install a package globally: **npm install -g <package name>**
>5. To check npm version: **npm -v**
<br>

**<h3>Commands NVM** :computer:</h3>
>1. To list all installations of NodeJS: **nvm ls**
>2. To list all available versions to install: **nvm ls-remote**
>3. To install a NodeJS version: **nvm install <version number>**
>5. To uninstall a NodeJS version: **nvm uninstall <version number>**
>6. To set default NodeJS version: **nvm alias default <version number>**

<br>

**<h1>Git Commands**</h1>

![Git Hub Picture](https://kinsta.com/wp-content/uploads/2018/04/what-is-github-1-1.png)
**<h3>Initializing**</h3>
<br>
Some commands are repeating but it is better for you to know all.

>1. The **git** program
>2. Starting a repository with **git init**
>3. The **.git** folder

**<h3>Basic workflow :computer:**</h3>
>1. Checking the status with: **git status**
>2. Staging files with: **git add**
>3. Using the: **.** shortcut to add all files, full command: **git add .**
>4. Creating a commit with: **git commit**
>5. Viewing the history with: **git log**
>6. Quick commits with git: **-am <message>**


<br>

**Git Commands (Leon)** :computer:
>1. Initialize Git: **git init**
>2. To add a file: git **add <file name>** or **git add .**  to add all files.
>3. To commit: **git commit -m "your message"**
>4. To check the logs: **git log**
>5. To check the status of the repo: **git status**
>6. To check the logs in one line: **git log --oneline**
>7. To link a repo on GitHub to your local repo: **git remote add origin <url>**
>8. To view a repo’s config: **git config -l**
>9. To view your Git global configuration: **git config -l --global**
>10. To view remote repo link:  **git remote -v**
>11. To pull changes from a repo on GitHub: **git pull**
>12. To push a branch and set upstream: **git push origin -u <branch name>**
>13. To push your changes to GitHub: **git push**
>14. To clone a repo: **git clone <repo ssh link>** 

To change the title of your main branch. 
>**git branch -M main** 
<br>
main is the new name of the branch.

To change the title of your default branch forever.

>**git config --global init.defaultBranch main**
<br>
main is the new name of the branch.



