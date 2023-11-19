FROM node:lts-alpine

WORKDIR /app

# Copy only the package.json and package-lock.json files
COPY app/package*.json /app

RUN npm install

COPY . .

EXPOSE 4000

CMD ["node", "app.js"]
