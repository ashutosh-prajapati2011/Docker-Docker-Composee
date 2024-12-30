FROM node:14
WORKDIR /app
COPY package*.json ./
EXPOSE 3000
RUN npm install
COPY . .
CMD [ "node" , "server.js" ]

