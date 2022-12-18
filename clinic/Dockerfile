FROM node:16-alpine
COPY plus_clinic/ /var/plus_clinic/
WORKDIR /var/plus_clinic/
RUN apk update &&\
    npm install -g npm
RUN npm install -y
EXPOSE 8080
CMD ["npm", "run", "serve"]