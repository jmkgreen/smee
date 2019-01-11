FROM node:latest

RUN pwd
ADD README.md package.json index.js test bin /
RUN npm install
RUN npm build

ENTRYPOINT ["node", "./smee.js"]
