# Iniciativa Kubedev 2022-06-12
# https://github.com/flbjuniorx-kubernetes/conversao-temperatura.git
FROM node:16.15.0
WORKDIR /app
COPY package*.json ./
RUN npm install
COPY . .
EXPOSE 8080
CMD ["node", "server.js"]