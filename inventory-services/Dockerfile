FROM node:18
WORKDIR /Cafe_Management_System/inventory-services
COPY package*.json ./
RUN npm install
COPY . .
EXPOSE 3000
CMD ["node", "index.js"]