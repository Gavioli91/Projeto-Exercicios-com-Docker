FROM node:14-alpine
EXPOSE 3001
ADD node_modules.tar.gz todo-app/todotests
COPY . /todo-app/todotests
ENTRYPOINT ["npm", "test"]
