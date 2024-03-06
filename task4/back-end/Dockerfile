# based on the latest ubuntu
FROM ubuntu:latest

# Update APT using apt-get update
RUN apt-get update

# Upgrade currently installed software through APT
RUN apt-get upgrade -y

# Install python3, python3-pip, and flask
RUN apt-get install -y python3 python3-pip
RUN pip3 install flask flask-cors

# Use /app as the working directory and copy the Python file to your Docker image
WORKDIR /app
COPY api.py /app/api.py

# default executable
EXPOSE 5252
CMD python3 api.py