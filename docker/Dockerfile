FROM     ubuntu:14.04
MAINTAINER adonisv79

# Install all prerequisites
RUN     apt-get -y update
RUN     apt-get -y install curl
RUN		apt-get -y install apt-transport-https
RUN     sh -c 'echo "deb [arch=amd64] https://apt-mo.trafficmanager.net/repos/dotnet-release/ trusty main" > /etc/apt/sources.list.d/dotnetdev.list'
RUN     apt-key adv --keyserver hkp://keyserver.ubuntu.com:80 --recv-keys 417A0893
RUN     apt-get -y update
RUN		apt-get -y install dotnet-dev-1.0.4

ENV      FILES_PATH /src/csharp-docker

# create src folder and upload the current branch's src folder
WORKDIR  $FILES_PATH
ADD      ./files $FILES_PATH

# Expose the service port
EXPOSE   80

CMD     ["bash"]