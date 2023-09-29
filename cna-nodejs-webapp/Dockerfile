FROM alpine

RUN apk add --update nodejs npm

COPY . /usr/src/app

WORKDIR /usr/src/app

# Install app dependencies
# A wildcard is used to ensure both package.json AND package-lock.json are copied
# where available (npm@5+)
COPY package*.json ./

RUN npm install
EXPOSE 8080
ENTRYPOINT [ "node", "server.js" ]
