FROM node:24-alpine
WORKDIR /app1
COPY package*.json ./
RUN npm install
COPY . /app1
EXPOSE 5001
CMD node index.js