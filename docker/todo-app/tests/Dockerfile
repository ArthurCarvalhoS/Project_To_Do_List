FROM mjgargani/puppeteer:trybe1.0
WORKDIR /todotest
ADD node_modules.tar.gz .
COPY . /todotest
ENTRYPOINT [ "npm", "test" ]