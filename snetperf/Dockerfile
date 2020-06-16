FROM ubuntu:18.04

# RUN apt update && apt install python3.6
RUN apt update && apt -y install \
    netperf
WORKDIR /usr/src/app

CMD [ "netserver", "-D" ]

