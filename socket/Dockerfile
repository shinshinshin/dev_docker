FROM node:16-alpine
WORKDIR /var/plus_socket
RUN apk update && npm install -g npm
RUN npm install
EXPOSE 8000
CMD ["npm", "run", "start"]