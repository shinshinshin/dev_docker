FROM node:16-alpine
WORKDIR /var/
RUN apk update &&\
    npm install -g npm
#COPY ./plus_clinic /var/plus_clinic
WORKDIR /var/plus_clinic
RUN npm install
EXPOSE 8080
CMD ["npm", "run", "serve"]