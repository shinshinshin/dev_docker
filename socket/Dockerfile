FROM node:16-alpine
COPY plus_socket/ /var/plus_socket/
WORKDIR /var/plus_socket/
RUN apk update &&\
    npm install -g npm &&\
    npm install
EXPOSE 8001
CMD ["npm", "run", "ts"]