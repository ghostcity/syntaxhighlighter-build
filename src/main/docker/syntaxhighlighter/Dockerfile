FROM node:0.10
LABEL Description="This image is used to provide an environment for projects being build on Node.js (0.10)" Vendor="informaticum.de" Version="1.0"
MAINTAINER Stefan Gasterstädt <stefan@gasterstädt.de>

RUN useradd -ms /bin/bash bob
RUN mkdir -p /home/bob/workspace
RUN chown -R bob:bob /home/bob/

USER bob
WORKDIR /home/bob/workspace
