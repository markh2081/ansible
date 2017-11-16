FROM node:6.10.3

RUN mkdir -p /opt/app
WORKDIR /opt/app
COPY . .

RUN npm install express

CMD ["node", "app.js"]

