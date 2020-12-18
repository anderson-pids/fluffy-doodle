FROM node:15.3.0-alpine3.11
WORKDIR /app
COPY package*.json ./
RUN npm install
COPY . .
EXPOSE 8080
CMD ["node","index.js"]