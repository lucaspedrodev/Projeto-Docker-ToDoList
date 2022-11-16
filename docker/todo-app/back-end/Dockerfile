FROM node:14-alpine

WORKDIR /docker/todo-app/back-end

EXPOSE 3001

ADD node_modules.tar.gz docker/todo-app/back-end

COPY ./ docker/todo-app/back-end

ENTRYPOINT [ "npm", "start" ]