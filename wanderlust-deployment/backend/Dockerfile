FROM node:21

WORKDIR /app
COPY . .

RUN npm install -g npm@10.8.0
RUN npm i

COPY .env.sample .env

EXPOSE 5000

CMD ["npm", "start"]

