FROM node:16-alpine
COPY plus_socket/ /var/plus_socket/
WORKDIR /var/plus_socket/
RUN apk update && npm install -g npm
RUN npm install
EXPOSE 8000
CMD ["npm", "run", "ts"]