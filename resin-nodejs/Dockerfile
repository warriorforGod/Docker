FROM resin/rpi-raspbian:latest
ENTRYPOINT []

RUN apt-get update && apt-get -qy install curl build-essential python ca-certificates

WORKDIR /root/
RUN curl -O https://nodejs.org/dist/v4.5.0/node-v4.5.0-linux-armv6l.tar.gz
RUN tar -xvf node-*.tar.gz -C /usr/local --strip-components=1

CMD ["node"]
