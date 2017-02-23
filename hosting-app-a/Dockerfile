FROM node:7-alpine

EXPOSE 8080

ADD package.json .
RUN npm install

ADD wwwroot wwwroot

CMD npm start