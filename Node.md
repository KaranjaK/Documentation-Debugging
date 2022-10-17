# Installing the Latest Stable Node version
1. Add the latest NODEJs PPA
    sudo apt-get install software-properties-common

    curl -sL https://deb.nodesource.com/setup_node-version | sudo -E bash -
2. Install latest NodeJs
    sudo apt-get install nodejs

# Uninstalling NodeJs
1. Remove the Node package
    sudo apt-get remove nodejs
2. Remove both the package file and configuration files
    sudo apt-get purge nodejs
3. Finally remove any unused files and free up space
    sudo apt-get autoremove

# Installing the Latest Stable version of npm

    npm install -g npm@latest

# Using Node Version Manager (nvm)
1. Check the various versions on Node installed
    nvm list
2. Change to the desired version of node
    nvm use (desired version)