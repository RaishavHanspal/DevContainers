FROM node:16

WORKDIR workspace/web-app

COPY package*.json ./
RUN npm install

COPY . .

CMD ["npm", "start"]