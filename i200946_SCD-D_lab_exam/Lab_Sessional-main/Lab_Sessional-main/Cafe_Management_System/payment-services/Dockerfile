FROM node:14-alpine
WORKDIR /Lab_Sessional-main/Cafe_Management_System/payment_services
COPY ["package.json", "package-lock.json", "./"]
RUN npm install
COPY . .
EXPOSE 3005
CMD ["npm", "start"]
