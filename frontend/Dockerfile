FROM node:20-alpine

WORKDIR /app

COPY package.json ./

RUN npm install

COPY . .

EXPOSE 5173

# truy cập được từ bên ngoài container
CMD ["npm", "run", "dev", "--", "--host"]