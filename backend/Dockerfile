FROM node:24.0.1-alpine

WORKDIR /backend

COPY package*.json ./
COPY .env ./
RUN npm install 
COPY . .
EXPOSE 5001

CMD ["npm", "start"]