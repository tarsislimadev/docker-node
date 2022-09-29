FROM node:lts-alpine

# RUN npm i -g surge live-server

WORKDIR /app

RUN git clone https://github.com/brtmvdl/surge.git && cd ./surge && npm link && cd .. && rm -rf ./surge 

ENV SURGE_EMAIL=

ENV SURGE_PASSWORD=
