# raspberry-docker

Upgrade you dist:

First, update your system's package list by entering the following command:

    sudo apt-get update

Next, upgrade all your installed packages to their latest versions with the command:

    sudo apt-get dist-upgrade
    
    
In last remove cache

    sudo apt-get clean
    
    
# Install last version of docker    
    
    curl -sSL https://get.docker.com | sh


There is a bug you need to downgrade to an old version (in case of Cgroup error)

    sudo apt-get install -y docker-ce=17.09.0~ce-0~raspbian --allow-downgrades
