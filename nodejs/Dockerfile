FROM node:8-alpine

WORKDIR /usr/src/app

COPY src/ .
RUN npm install

EXPOSE 8080
CMD [ "npm", "start" ]