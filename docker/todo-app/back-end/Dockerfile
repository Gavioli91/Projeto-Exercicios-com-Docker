FROM node:14-alpine
EXPOSE 3001
ADD node_modules.tar.gz todo-app/back-end
COPY . /todo-app/back-end
ENTRYPOINT ["npm", "start"]
