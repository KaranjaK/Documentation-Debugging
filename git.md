# GIT AND GITHUB HANDBOOK

## Updating GIT

1. sudo add-apt-repository ppa:git-core/ppa
2. sudo apt update
3. sudo apt install git
4. git --version

## Configuring SSH

1. git config --global color.ui true
2. git config --global user.name <Full Names of the user>
3. git config --global user.email <Email used to open the github account being confugured>
4. git config --global init.defaultBranch main/master
5. ssh-keygen <Ensure you press enter for every prompt with no passphase being entered>
6. cd .ssh
7. ls
8. cat id_rsa.pub
9. Move to the github account settings, under SSH and GPG Keys tab, click <New SSH Key> under SSH Keys and paster the copied by the above command in the key input tab

## Check the current Remote Git Repo you are connected

git remote -v

## Detach local git repo from remote git repo

git remote rm origin
