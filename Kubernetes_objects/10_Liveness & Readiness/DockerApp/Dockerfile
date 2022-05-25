FROM node:166666-buster as builder
WORKDIR /app
COPY . .
RUN npm install
EXPOSE 3000

CMD ["npm", "start"]


