FROM node:12-alpine as worker

WORKDIR "/app"

COPY package.json .

RUN npm install

COPY . .

CMD ["npm", "run", "start"]