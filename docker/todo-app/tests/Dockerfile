FROM node:14-alpine
EXPOSE 3001
ADD node_modules.tar.gz todo-app/tests
COPY . /todo-app/tests
ENTRYPOINT ["npm", "test"]
