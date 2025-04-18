FROM node:18
WORKDIR /Cafe_Management_System/order-services
COPY package*.json ./
RUN npm install
COPY . .
EXPOSE 3000
CMD ["node", "index.js"]