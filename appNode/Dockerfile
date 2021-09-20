FROM node:12.18.1

WORKDIR /app

RUN npm init & npm install express --save

COPY . .

EXPOSE 3000

CMD ["node", "app.js"];