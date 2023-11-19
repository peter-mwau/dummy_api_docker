FROM node:lts-alpine

WORKDIR /app

# Copy only the package.json and package-lock.json files
COPY package*.json .

RUN npm install

COPY . .

EXPOSE 4000

CMD ["node", "app.js"]
