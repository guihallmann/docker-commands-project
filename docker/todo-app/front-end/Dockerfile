FROM node:14-alpine
WORKDIR /docker/todo-app/back-end
ADD node_modules.tar.gz ./back-end
COPY . .
EXPOSE 3000
CMD ['npm', 'start']
# https://docs.docker.com/engine/reference/builder/
