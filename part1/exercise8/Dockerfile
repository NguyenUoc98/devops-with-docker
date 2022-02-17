FROM ubuntu:20.04

WORKDIR /usr/src/app

RUN apt update && apt upgrade -y

RUN apt install curl -y

COPY script-v2.sh .

RUN chmod +x script-v2.sh

ENTRYPOINT ["./script-v2.sh"]
