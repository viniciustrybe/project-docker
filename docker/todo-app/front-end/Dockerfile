FROM node:14-alpine
EXPOSE 3000
WORKDIR /todofront
ADD node_modules.tar.gz .
COPY package.json .
COPY package-lock.json .
RUN npm install
COPY . .
CMD [ "npm", "start" ]

