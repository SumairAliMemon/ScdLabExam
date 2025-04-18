# Use official Node.js LTS version as base image
FROM node:23

WORKDIR /app

COPY package.json package-lock.json ./

RUN npm install

COPY . .

EXPOSE 3001

CMD ["node", "index.js"]
