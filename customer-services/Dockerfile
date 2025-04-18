FROM node:18
WORKDIR /Cafe_Management_System/customer-service
COPY package*.json ./
RUN npm install
COPY . .
EXPOSE 3000
CMD ["node", "index.js"]