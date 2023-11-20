FROM node:lts-alpine

RUN npm install -g nodemon

WORKDIR /app

# Copy only the package.json and package-lock.json files
COPY /package*.json .

RUN npm install

COPY . .

EXPOSE 4000

CMD ["npm", "run", "dev"]
