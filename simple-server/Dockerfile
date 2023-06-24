# Base image
FROM node:19.5.0-alpine

# Install deps
WORKDIR /usr/app
COPY ./src ./
RUN npm install

# Default commands
CMD [ "npm", "start" ]