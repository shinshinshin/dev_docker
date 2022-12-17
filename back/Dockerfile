FROM node:16-alpine
WORKDIR /var/plus_back
RUN apk update &&\
    npm install -g npm
COPY ./plus_back /var/plus_back
RUN npm install
EXPOSE 8000
CMD ["npm", "run", "start"]