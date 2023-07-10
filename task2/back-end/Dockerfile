# use latest Ubuntu as base image
FROM ubuntu:latest

# update APT
RUN apt-get update
RUN apt-get upgrade -y
RUN apt-get install -y python3 python3-pip
RUN pip3 install flask

# set working directory
WORKDIR /app
COPY , /app

EXPOSE 5252

CMD ["python3", "api.py"]
