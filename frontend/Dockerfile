FROM node:22-alpine

WORKDIR /app

COPY . .

RUN yarn install --production

EXPOSE 3000

CMD ["npm", "start"]