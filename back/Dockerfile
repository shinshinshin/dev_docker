FROM node:16-alpine
COPY plus_back/ /var/plus_back/
WORKDIR /var/plus_back
RUN apk update &&\
    npm install -g npm &&\
    apk add mysql-client &&\
    npm install
#RUN npm run db:setup:dev
EXPOSE 8000
CMD ["npm", "run", "nodemon"]