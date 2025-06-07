FROM node:22.11.0-alpine

EXPOSE 3000

WORKDIR /usr/app

COPY . .

RUN npm ci
RUN npm run build

CMD npm run start
