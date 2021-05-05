FROM node:latest AS build

WORKDIR /home/node/sonos-doorbell-api
RUN git clone https://github.com/seimonw/sonos-doorbell-api .
RUN npm i
ENV DEBUG=true
CMD ["npm", "start"]

