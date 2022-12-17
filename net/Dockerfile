FROM node:16-alpine
WORKDIR /var/plus_net
RUN apk update && npm install -g npm && npm install
EXPOSE 8080
CMD ["npm","run","serve"]