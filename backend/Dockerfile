FROM node:alpine

WORKDIR /app

COPY package.json .

RUN npm install

COPY . .

EXPOSE 8000

ENV MONGODB_USERNAME=memo
ENV MONGODB_PASSWORD=verysecretpassword

CMD ["npm", "start"]