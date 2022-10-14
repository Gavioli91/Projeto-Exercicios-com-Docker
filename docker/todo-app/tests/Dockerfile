FROM mjgargani/puppeteer:trybe1.0
WORKDIR /todo-app/tests
ADD node_modules.tar.gz .
COPY . .
CMD ["npm", "test"]
