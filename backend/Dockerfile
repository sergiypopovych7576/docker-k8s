FROM node:20

WORKDIR /app

COPY package.json .

RUN npm install

COPY . .

EXPOSE 80

ENV MONGO_CONNECTION=mongodb://mongodb-service.popov-test.svc.cluster.local:27017/course-goals

CMD ["node", "app.js"]