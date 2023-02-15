FROM node:14 as todobackend
EXPOSE 3001
ADD node_modules.tar.gz .
COPY . todobackend
ENTRYPOINT [ "npm", "start" ]
