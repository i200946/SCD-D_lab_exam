FROM node:14-alpine
WORKDIR /Lab_Sessional-main/Cafe_Management_System/customer-services
COPY ["package.json", "package-lock.json", "./"]
RUN npm install
COPY . .
EXPOSE 3001
CMD ["npm", "start"]
