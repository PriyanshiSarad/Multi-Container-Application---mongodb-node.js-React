FROM node:14

WORKDIR /app

COPY package.json /app
RUN npm install && npm audit fix

COPY . .

EXPOSE 3000

CMD [ "npm", "start" ]