FROM node:14-alpine
WORKDIR /todo-app/tests
ADD node_modules.tar.gz .
COPY . .
CMD ["npm", "test"]
