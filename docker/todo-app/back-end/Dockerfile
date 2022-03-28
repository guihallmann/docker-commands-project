FROM node:14-alpine
WORKDIR /docker/todo-app/back-end
ADD node_modules.tar.gz ./back-end
EXPOSE 3001
CMD ['npm', 'start']
# https://docs.docker.com/engine/reference/builder/