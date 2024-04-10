FROM node:16

#Create app directory
WORKDIR /~/Downloads/github-actions-ci-base

#Install app dependencies
COPY package*.json ./

RUN npm Install

#bundle app source
COPY . .

EXPOSE 8080
CMD [ "node", "server.js" ]
