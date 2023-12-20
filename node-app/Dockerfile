FROM node:alpine

WORKDIR /app

COPY index.js .

RUN npm install

ENTRYPOINT ["node", "index.js", "package.json"] 
