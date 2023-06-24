# Base image
FROM node:19.5.0-alpine

WORKDIR /usr/app

# Install deps
COPY ./src/package.json ./
RUN npm install
COPY ./src ./

# Default commands
CMD [ "npm", "start" ]