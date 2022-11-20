FROM node

WORKDIR /app

COPY package.json /app
RUN npm install -g npm@9.1.2
RUN npm install

COPY . /app

EXPOSE 80

ENV MONGODB_USERNAME=root
ENV MONGODB_PASSWORD=secret

CMD ["npm", "start"]