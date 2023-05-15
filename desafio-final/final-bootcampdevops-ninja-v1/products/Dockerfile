FROM node:16-alpine

WORKDIR /products

COPY package*.json /app

RUN npm install

COPY . /app


ENV PORT=3001
ENV PRODUCTS_SERVICE=host.docker.internal
ENV SHOPPING_CART_SERVICE=host.docker.internal

EXPOSE $PORT

CMD ["npm","start"]
