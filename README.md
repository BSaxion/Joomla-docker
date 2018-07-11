# Joomla-docker
#This contains two containers pulled from two images.
# The first container is Joomla pulled from the official Joomla image.
#According to the official docker image of Joomla, Joomla should be linked to the mysql image.
#So we have linked it.
# The only thing you need to do is just run "docker-compose up -d" and then you will see all the containers are up.
# This is also designed to work the as local which means I have also created volumes for both the Joomla sources and the MySQL.
# Using docker, you don't need to install the mysql, don't to care about anything but the docker image with the docker-compose yaml file takes care of it.
