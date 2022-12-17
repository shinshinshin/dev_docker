FROM node:16-alpine
WORKDIR /var/plus_socket
RUN apk update && npm install -g npm
COPY ./plus_socket /var/plus_socket
RUN npm install
EXPOSE 8000
CMD ["npm", "run", "start"]