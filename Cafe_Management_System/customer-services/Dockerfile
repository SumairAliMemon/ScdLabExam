# Use official Node.js LTS version as base image
FROM node:20

WORKDIR /app

COPY package.json package-lock.json ./

RUN npm install

COPY . .

EXPOSE 3005

CMD ["node", "index.js"]
