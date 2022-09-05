FROM ubuntu:20.04

RUN apt-get update && apt-get -y install curl

# If OS is not Windows then uncomment the following to give permission to execute the file
# RUN chmod +x command.sh

COPY command.sh .

CMD ./command.sh