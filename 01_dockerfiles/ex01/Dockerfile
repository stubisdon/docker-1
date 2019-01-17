FROM debian
RUN apt-get update -y && apt-get upgrade -y 
RUN	apt-get install -y wget bzip2
CMD wget http://dl.4players.de/ts/releases/3.0.13.8/teamspeak3-server_linux_amd64-3.0.13.8.tar.bz2
CMD tar xfvj teamspeak3-server_linux_amd64-3.0.13.8.tar.bz2
CMD sh teamspeak3-server_linux_amd64/ts3server_startscript.sh
