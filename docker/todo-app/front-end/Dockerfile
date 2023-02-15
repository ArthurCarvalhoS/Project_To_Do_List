FROM node:14
WORKDIR /todoapp
EXPOSE 3000
ADD node_modules.tar.gz .
COPY . /todoapp
ENTRYPOINT [ "npm", "start" ]