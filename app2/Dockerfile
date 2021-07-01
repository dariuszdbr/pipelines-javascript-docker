FROM node:8

WORKDIR /usr/src/app2

COPY package*.json ./
RUN npm ci --only=production

COPY . .

EXPOSE 8081
CMD [ "npm", "start" ]