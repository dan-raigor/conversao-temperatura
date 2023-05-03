FROM node:16.13.2
WORKDIR /app
# com asterísco inclui tanto o package.json quanto o package-lock.json
COPY package*.json ./
RUN npm install
COPY . .
CMD ["node", "server.js"]