FROM node:12-alpine
WORKDIR /app
COPY package*.json /app
RUN npm install

# Bundle app source
COPY . .

EXPOSE 8081
CMD [ "npm", "start" ]