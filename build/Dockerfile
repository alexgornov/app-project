FROM node:15-alpine
RUN apk add --update --no-cache python2 make g++

ADD . /opt
WORKDIR /opt
RUN yarn install
RUN yarn build

EXPOSE 50500
CMD [ "yarn", "start" ]
