# List of all available docker-compose releases
https://github.com/docker/compose/releases

#Let us install a specific version

``
sudo curl -L https://github.com/docker/compose/releases/download/1.29.2/docker-compose-`uname -s`-`uname -m` -o /usr/local/bin/docker-compose
``

#Provide execute permissions

``
sudo chmod +x /usr/local/bin/docker-compose
``

#Check if you are able to run docker-compose

``
docker-compose --version
``
