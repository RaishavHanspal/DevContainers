FROM node:16

WORKDIR workspace/server

COPY package*.json ./
RUN npm install

COPY . .

CMD ["npm", "start"]