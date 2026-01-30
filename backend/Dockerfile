FROM node:20-alpine

WORKDIR /app

# Docker cache)
COPY package.json ./

RUN npm install

COPY . .

EXPOSE 5001
CMD ["npm", "start"]