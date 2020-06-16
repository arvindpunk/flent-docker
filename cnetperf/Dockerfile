FROM ubuntu:18.04

# RUN apt update && apt install python3.6
RUN apt update && apt -y install \
    netperf \
    flent
WORKDIR /usr/src/app

CMD [ "echo", "${PATH}" ]

