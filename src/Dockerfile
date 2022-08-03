FROM node:16.16.0
WORKDIR /app
COPY ./package*.json ./
RUN npm install
RUN npm install bootstrap@5.2.0
COPY . . 
EXPOSE 8080
CMD ["node", "server.js"]