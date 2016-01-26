FROM ubuntu
MAINTAINER Frank Förster <frank.foerster@uni-wuerzburg.de>

# Update the installation and remove openjdk
RUN apt-get update && apt-get --assume-yes dist-upgrade && apt-get --assume-yes autoremove && apt-get --assume-yes purge openjdk* 
