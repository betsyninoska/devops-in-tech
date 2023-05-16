FROM node:lts-alpine
WORKDIR /express-frontend
COPY requirements.txt /app
RUN pip install -r requirements.txt
COPY . .
ENV PORT=3000
EXPOSE $PORT
CMD [ "node", "server.js" ]
