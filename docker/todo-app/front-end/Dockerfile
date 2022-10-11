FROM node:14-alpine
EXPOSE 3001
ADD node_modules.tar.gz todo-app/front-end
COPY . /todo-app/front-end
ENTRYPOINT ["npm", "start"]
