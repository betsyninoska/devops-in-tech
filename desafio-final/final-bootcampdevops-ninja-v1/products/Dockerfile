FROM node:lts-alpine
WORKDIR /express-product
COPY requirements.txt /app
RUN pip install -r requirements.txt
COPY . .
EXPOSE 3001
CMD [ "node", "server.js" ]
