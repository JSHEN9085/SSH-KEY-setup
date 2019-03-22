1. For Windows
(1) Make sure you have git, https://git-scm.com/downloads. It generally comes pre-installed with most operating systems, but you can check by running 'git version' on terminal. In your terminal, set
PATH=C:\Program Files\Git\bin\
(2) Run 'ssh-keygen' to create a new SSH key. If you do not already have an SSH key set up, you’ll be asked to select a location and a passphrase. Just leave everything blank and press enter for default location and no passphrase. If you’re asked if you want to overwrite, then you already have an SSH key and you do not want to overwrite it.
(3) 'cat ~/.ssh/id_rsa.pub' This will display your SSH key to your terminal. You want to then copy this and add this SSH key to your github by following the instructions posted on https://help.github.com/en/articles/adding-a-new-ssh-key-to-your-github-account.
(4) You need to let git know who you are. You can do this by running:
git config --global user.email "you@example.com"
git config --global user.name "Your Name"
(5) Let github remember your username and password, https://help.github.com/en/articles/caching-your-github-password-in-git



2. For Mac
(1) Make sure you have git. It generally comes pre-installed with most operating systems, but you can check by running 'git version' on terminal. If this gives you an error or does not come back with version number, you'll need to install git. you can get it by typing 'brew install git'  on your terminal.
(2) Run 'ssh-keygen' to create a new SSH key. If you do not already have an SSH key set up, you’ll be asked to select a location and a passphrase. Just leave everything blank and press enter for default location and no passphrase. If you’re asked if you want to overwrite, then you already have an SSH key and you do not want to overwrite it.
(3) 'cat ~/.ssh/id_rsa.pub' This will display your SSH key to your terminal. You want to then copy this and add this SSH key to your github by following the instructions posted on https://help.github.com/en/articles/adding-a-new-ssh-key-to-your-github-account.
(4) You need to let git know who you are. You can do this by running:
git config --global user.email "you@example.com"
git config --global user.name "Your Name"
(5) Let github remember your username and password, https://help.github.com/en/articles/caching-your-github-password-in-git
