FROM node:16-alpine3.15
WORKDIR /work
COPY package*.json ./
RUN npm install
COPY . .
CMD [ "npm", "run", "dev" ]

FROM node:16-alpine3.15
WORKDIR /work
COPY . .
RUN npm install
CMD [ "npm", "run", "dev" ]