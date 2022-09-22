FROM mjgargani/puppeteer:trybe1.0 AS todofrontend

WORKDIR /todo-app/tests/

ADD node_modules.tar.gz .

COPY . .

ENTRYPOINT [ "npm", "test" ]