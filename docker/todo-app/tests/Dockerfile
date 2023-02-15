FROM mjgargani/puppeteer:trybe1.0 as todotests
ADD node_modules.tar.gz .
COPY . todotests
ENTRYPOINT [ "npm", "test" ]