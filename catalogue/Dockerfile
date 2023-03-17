FROM node:14-alpine

EXPOSE 8080

WORKDIR /opt/server

COPY package.json /opt/server/
#npm install get dependiencies of node js project
RUN npm install
#copy the server.js files 
COPY server.js /opt/server/

CMD ["node", "server.js"]

