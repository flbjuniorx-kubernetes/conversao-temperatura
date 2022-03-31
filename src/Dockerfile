FROM node
WORKDIR /app
COPY package*.json ./
RUN npm install
COPY . .
EXPOSE port 8080
CMD ["node", "server.js"]