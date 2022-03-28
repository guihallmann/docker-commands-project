FROM mjgargani/puppeteer:trybe1.0
WORKDIR /docker/todo-app/tests
ADD node_modules.tar.gz ./tests
COPY . .
EXPOSE 3000
CMD ['npm', 'test']
# https://docs.docker.com/engine/reference/builder/
