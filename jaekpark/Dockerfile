FROM		debian:buster


RUN apt-get update && apt-get -y upgrade &&\
	apt-get install -y sudo yarn vim curl wget

WORKDIR		/usr/app

COPY 		. .

ENTRYPOINT	["bash", "entrypoint.sh"]
