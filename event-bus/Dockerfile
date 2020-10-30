FROM node:alpine

WORKDIR /app
COPY package.json ./
RUN npm config set strict-ssl false
RUN npm install
RUN npm install nodemon
COPY ./ ./
CMD ["npm", "start"]
