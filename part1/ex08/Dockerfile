# starts from ubuntu:20.04
FROM ubuntu:20.04

# install curl into that image
RUN apt-get update && apt-get -y upgrade

RUN apt-get -y install curl

# specify working directory
WORKDIR /usr/src/app

# copy the script to that location
COPY website.sh .

# run script when starting container
CMD ./website.sh