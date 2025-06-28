FROM node:24.0.1-alpine

WORKDIR /frontend

COPY package*.json ./
COPY .env ./
RUN npm install --legacy-peer-deps
COPY . .
EXPOSE 5173

CMD ["npm", "run", "dev"]