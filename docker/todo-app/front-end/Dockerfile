FROM node:14 as todofrontend
EXPOSE 3000
ADD node_modules.tar.gz .
COPY . todofrontend
ENTRYPOINT [ "npm", "start" ]